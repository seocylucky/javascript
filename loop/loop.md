# �ݺ���
## while
```ts
while(true) {
    document.write('coding everybody <br />');
} // ���ѹݺ�, true�� fasle�� �ٲٸ� ������� ���� ���̴�.
```
���ѹݺ��� ���� �ʵ��� ������ �����ϸ�?
```ts
var i = 0;
while(i < 10) {
    document.write('coding everybody ' + i + '<br />');
    i = i + 1;
}
//��� ���
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
while�� ���� �� ���� �� �ִ� ������()
```ts
for(var i = 0; i < 10; i++) {
    document.write('coding everybody ' + i + '<br />');
}
//��� ���
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