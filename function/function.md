# 함수
함수는 코드의 재사용성, 유지보수, 가독성을 갖게 한다.
### 함수의 형식
```ts
function 함수명 (인자) {
        코드
        return 반환값
    }
```
example
```ts
function numbering() {
    document.write(1)
}
numbering(); // 1
```
# 입력
## 인자
함수로 유입되는 입력 값.
```ts
function get_argument(arg) {
    return arg;
}
alert(get_argument(1)); // 1
alert(get_argument(2)); // 2
```
## 복수의 인자
```ts
function get_arguments(arg1, arg2) {
    return arg1 + arg2
}
alert(get_arguments(10, 20)); // 30
alert(get_arguments(20, 30)); // 50
```
# 출력
## return
return은 뒤에 따라오는 값을 **함수의 결과**로 반환한다. 동시에 **함수를 종료**시킨다.
```ts
function get_member1() {
    return 'seocylucky'
}
get_member1(); // seocylucky
```
return이 여러개 와도 첫번째 return에서 바로 함수가 종료됨으로, 123이 출력한다.
```ts
function get_member2() {
    return '123';
    return '456';
    return '789';
}
get_member2(); // 123만 출력
```
# 함수의 다양한 정의 방법
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
## 익명함수
정의와 호출을 같이 한다.
```ts
(function () {
    i = 0;
    while(i < 10) {
        document.write(i);
        i += 1;
    }
})();
```