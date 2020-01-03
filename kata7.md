* https://www.codewars.com/kata/factorial-1/train/javascript
```js
function factorial(n){
 let res = 1;
  if(n === 0){
res = 1;
}
  for(let i = n; i > 0; i--){
res *= i ;
}
return res;
}
```