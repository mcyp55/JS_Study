배열 = 여러가지 종류를 나열해서 넣을수 있는 값

키포인트 [], .push(), .length
.push() // 배열을 추가시킬 수 있다.
.length  // 배열의 크기(갯수)를 알 수 있다.

```js
const array = [
 1, true, {a: 1}, [1,2,3,4]
];
```
```js
console.log(array[2])  // {a:1}
```js
array.push(6)

console.log(array[5]) // 6

console.log(array.length)
