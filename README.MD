## refactoryExamBirthdayCakeCandles

- Problem name : Birthday Cake Candles

- Author : by shashank21j

- url: https://www.hackerrank.com/challenges/birthday-cake-candles/problem

- Pseudocode
```
function birthdayCakeCandles(n, ar) {
   
    let max = 0;
    for(let i = 0; i < ar.length; i++) {
        if(ar[i] > max) {
            max = ar[i];
        }
    }
    let count = 0;
    for(let i = 0; i < ar.length; i++) {
        if(ar[i] === max) {
            count++;
        }
    }
    return count;
}


```
- How to run the program
  save it or clone it to your local repo then run the program with nodejs following this command
```
 node BirthdayCakeCandles.js

```
 dont forget to ```console.log``` the program to see output
