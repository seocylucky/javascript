# �ݺ����� ����
## break
�ݺ� �۾��� �߰��� �ߴܽ�Ű�� ���� �� ����Ѵ�.
```ts
for(var i = 0; i < 10; i++) {
    if(i === 5) {
        break;
    }
    document.write('coding everybody ' + i + '<br />');
}
//��� ���
/* coding everybody 0
   coding everybody 1
   coding everybody 2
   coding everybody 3
   coding everybody 4 */
```
## continue
�ش� ������ �ߴܽ�Ű�� �ٽ� ���� �������� �ݺ����� �����Ų��.
```ts
for(var i = 0; i < 10; i++) {
    if(i === 5) {
        continue;
    }
    document.write('coding everybody ' + i + '<br />');
}
//��� ���
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