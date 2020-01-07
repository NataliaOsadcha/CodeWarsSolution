* https://www.codewars.com/kata/even-or-odd/train/javascript
```js
function even_or_odd(number) {
 return number %2 ? "Odd" : "Even"
}
```
* https://www.codewars.com/kata/554e122a3d116a4e52000040/train/javascript
```js
const Round = n => n.toFixed(2)
```
* https://www.codewars.com/kata/round-a-number-to-n-decimal-places/train/javascript
```js
Round = (n,p) => n.toFixed(p)
```
* https://www.codewars.com/kata/sum-without-highest-and-lowest-number/train/javascript
```js
sumArray = a => a ? a.sort((x, y) => x - y).slice(1, -1).reduce((s, e) => s + e, 0) : 0
```
* https://www.codewars.com/kata/squash-the-bugs/train/javascript
```js
const findLongest = str => Math.max(...str.split(' ').map(word=>word.length))
```
* https://www.codewars.com/kata/57cc975ed542d3148f00015b/train/javascript
```js
const check = (a,x) => a.includes(x);
//OR
function check(a,x){
   for (i = 0; i<a.length; i++){
   if (a[i] ===x) return true;
};return false

};
```