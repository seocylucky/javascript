# �� ������
## && (and ������)
&&�� ���װ� ������ ��� ��(true)�� �� ���� �ȴ�. 
```ts
if(true && true) {
    alert(1);
} // 1
if(true && false) {
    alert(2);
} //��� x
if(false && true) {
    alert(3);
} //��� x
if(false && false) {
    alert(4);
} //��� x
```
example
```ts
var id = prompt('���̵� �Է����ּ���.');
var password = prompt('��й�ȣ�� �Է����ּ���.');
if(id == 'seocylucky' && password === '111111') {
    alert('�ݰ����ϴ�. ' + id + '��.');
} else {
    alert('���̵� ��й�ȣ�� ��ġ���� �ʽ��ϴ�.');
}
```
## || (or ������)
 ||�� ���װ� ���� �� �ϳ��� true�� �ִٸ� true�̴�.
```ts
if(true || true) {
    alert(1);
} // 1
if(true || false) {
    alert(2);
} // 2
if(false || true) {
    alert(3);
} // 3
if(false || false) {
    alert(4);
} // ��� X
```
example
```ts
var id = prompt('���̵� �Է����ּ���.');
var password = prompt('��й�ȣ�� �Է����ּ���.');
if((id === 'seocylucky' || id === 'ttytty456') && password === '111111') {
    alert('�����߽��ϴ�.');
} else {
    alert('������ �����߽��ϴ�.');
}
```
## ! (not ������)
!�� ������ �ǹ̷�,true�� false��, false�� true�� �ٲ۴�.
```ts
if(!true && !true) {
    alert(1);
} // ��� x
if(!false && !true) {
    alert(2);
} // ��� x
if(!false && !false) {
    alert(3);
} // 3
```
## Boolean�� ��ü��
0�� false, 0�� �ƴ� ���� true�� �����Ѵ�. 
### **false�� ���ֵǴ� ��Ÿ ������ ��**
�ؿ� �������� ��� �� if�� ������ false�̹Ƿ� ��� ���� ��Ÿ���� �ʴ´�.
```ts
if('') {
    alert('���ڿ�');
}
if(undefined) {
    alert('undefined');
}
```
```ts
var a;
if(a) {
    alert('���� �Ҵ���� ���� ����');
}
```
```ts
if(null) {
    alert('null');
}
if('NaN') {
    alert('NaN');
}
```