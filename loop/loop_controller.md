# 반복문의 제어
## break
반복 작업을 중간에 중단시키고 싶을 때 사용한다.
```ts
for(var i = 0; i < 10; i++) {
    if(i === 5) {
        break;
    }
    document.write('coding everybody ' + i + '<br />');
}
//출력 결과
/* coding everybody 0
   coding everybody 1
   coding everybody 2
   coding everybody 3
   coding everybody 4 */
```
## continue
해당 순간만 중단시키고 다시 다음 순서부터 반복문을 실행시킨다.
```ts
for(var i = 0; i < 10; i++) {
    if(i === 5) {
        continue;
    }
    document.write('coding everybody ' + i + '<br />');
}
//출력 결과
/* coding everybody 0
   coding everybody 1
   coding everybody 2
   coding everybody 3
   coding everybody 4
   coding everybody 6
   coding everybody 7
   coding everybody 8
   coding everybody 9 */
```