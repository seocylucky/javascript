# �Լ�
�Լ��� �ڵ��� ���뼺, ��������, �������� ���� �Ѵ�.
### �Լ��� ����
```ts
function �Լ��� (����) {
        �ڵ�
        return ��ȯ��
    }
```
example
```ts
function numbering() {
    document.write(1)
}
numbering(); // 1
```
# �Է�
## ����
�Լ��� ���ԵǴ� �Է� ��.
```ts
function get_argument(arg) {
    return arg;
}
alert(get_argument(1)); // 1
alert(get_argument(2)); // 2
```
## ������ ����
```ts
function get_arguments(arg1, arg2) {
    return arg1 + arg2
}
alert(get_arguments(10, 20)); // 30
alert(get_arguments(20, 30)); // 50
```
# ���
## return
return�� �ڿ� ������� ���� **�Լ��� ���**�� ��ȯ�Ѵ�. ���ÿ� **�Լ��� ����**��Ų��.
```ts
function get_member1() {
    return 'seocylucky'
}
get_member1(); // seocylucky
```
return�� ������ �͵� ù��° return���� �ٷ� �Լ��� ���������, 123�� ����Ѵ�.
```ts
function get_member2() {
    return '123';
    return '456';
    return '789';
}
get_member2(); // 123�� ���
```
# �Լ��� �پ��� ���� ���
example 1
```ts
numbering = function () {
    i = 0;
    while(i < 10) {
        document.write(i);
        i += 1;
    }
}
numbering();
```
example 2
```ts
function numbering() {
    i = 0;
    while(i < 10) {
        document.write(i);
        i += 1;
    }
}
numbering();
```
## �͸��Լ�
���ǿ� ȣ���� ���� �Ѵ�.
```ts
(function () {
    i = 0;
    while(i < 10) {
        document.write(i);
        i += 1;
    }
})();
```