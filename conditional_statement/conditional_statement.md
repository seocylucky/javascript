# ���ǹ�
## if
���ǹ��� if�� ����. �ڿ� ������ �� �� �ִ� ���� Boolean���̴�.
```ts
if(true) {
    alert('result : true');
}
```
�� ���� ����� result : true �̴�.
```ts
if(false) {
    alert('result : true');
}
```
�ƹ��͵� ������� ���� ���̴�.
## else
if�� ������ false�� ���, ���� else�� �߰�ȣ�� ����ȴ�.
```ts
if(true) {
    alert(1);
} else {
    alert(2);
}
```
�� ����� 1
```ts
if(false) {
    alert(1);
} else {
    alert(2);
}
```
�� ����� 2
## else if
else if�� �� �پ��� ������ �����Ѵ�. if�� else�� �ٸ��� ���� ���� �� �� �ִ�. else if�� ��� ������ false��� else�� ����ȴ�. (else�� ���� ����)
```ts
if(false) {
    alert(1);
} else if(true) {
    alert(2);
} else if(true) {
    alert(3);
} else {
    alert(4);
}
```
�� ����� 2
```ts
if(false) {
    alert(1);
} else if(false)) {
    alert(2);
} else if(true) {
    alert(3);
} else {
    alert(4);
}
```
�� ����� 3