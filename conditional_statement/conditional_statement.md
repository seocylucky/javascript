# 조건문
## if
조건문은 if로 시작. 뒤에 조건이 될 수 있는 값은 Boolean값이다.
```ts
if(true) {
    alert('result : true');
}
```
위 실행 결과는 result : true 이다.
```ts
if(false) {
    alert('result : true');
}
```
아무것도 출력하지 않을 것이다.
## else
if의 조건이 false일 경우, 다음 else의 중괄호가 실행된다.
```ts
if(true) {
    alert(1);
} else {
    alert(2);
}
```
위 결과는 1
```ts
if(false) {
    alert(1);
} else {
    alert(2);
}
```
위 결과는 2
## else if
else if는 더 다양한 조건을 제공한다. if와 else와 다르게 여러 개가 올 수 있다. else if의 모든 조건이 false라면 else가 실행된다. (else는 생략 가능)
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
위 결과는 2
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
위 결과는 3