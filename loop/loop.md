# 반복문
## while
```ts
while(true) {
    document.write('coding everybody <br />');
} // 무한반복, true를 fasle로 바꾸면 출력하지 않을 것이다.
```
무한반복이 되지 않도록 범위를 설정하면?
```ts
var i = 0;
while(i < 10) {
    document.write('coding everybody ' + i + '<br />');
    i = i + 1;
}
//출력 결과
/* coding everybody 0
   coding everybody 1
   coding everybody 2
   coding everybody 3
   coding everybody 4
   coding everybody 5
   coding everybody 6
   coding everybody 7
   coding everybody 8
   coding everybody 9 */
```
## for
while을 썼을 때 나올 수 있는 문제점()
```ts
for(var i = 0; i < 10; i++) {
    document.write('coding everybody ' + i + '<br />');
}
//출력 결과
/* coding everybody 0
   coding everybody 1
   coding everybody 2
   coding everybody 3
   coding everybody 4
   coding everybody 5
   coding everybody 6
   coding everybody 7
   coding everybody 8
   coding everybody 9 */
```