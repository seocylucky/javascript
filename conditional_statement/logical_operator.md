# 논리 연산자
## && (and 연산자)
&&는 좌항과 우항이 모두 참(true)일 때 참이 된다. 
```ts
if(true && true) {
    alert(1);
} // 1
if(true && false) {
    alert(2);
} //출력 x
if(false && true) {
    alert(3);
} //출력 x
if(false && false) {
    alert(4);
} //출력 x
```
example
```ts
var id = prompt('아이디를 입력해주세요.');
var password = prompt('비밀번호를 입력해주세요.');
if(id == 'seocylucky' && password === '111111') {
    alert('반갑습니다. ' + id + '님.');
} else {
    alert('아이디나 비밀번호가 일치하지 않습니다.');
}
```
## || (or 연산자)
 ||는 좌항과 우항 중 하나라도 true가 있다면 true이다.
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
} // 출력 X
```
example
```ts
var id = prompt('아이디를 입력해주세요.');
var password = prompt('비밀번호를 입력해주세요.');
if((id === 'seocylucky' || id === 'ttytty456') && password === '111111') {
    alert('인증했습니다.');
} else {
    alert('인증에 실패했습니다.');
}
```
## ! (not 연산자)
!는 부정의 의미로,true를 false로, false를 true로 바꾼다.
```ts
if(!true && !true) {
    alert(1);
} // 출력 x
if(!false && !true) {
    alert(2);
} // 출력 x
if(!false && !false) {
    alert(3);
} // 3
```
## Boolean의 대체제
0은 false, 0이 아닌 값은 true로 간주한다. 
### **false로 간주되는 기타 데이터 형**
밑에 예제들은 모두 다 if의 조건이 false이므로 출력 값이 나타나지 않는다.
```ts
if('') {
    alert('빈문자열');
}
if(undefined) {
    alert('undefined');
}
```
```ts
var a;
if(a) {
    alert('값이 할당되지 않은 변수');
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