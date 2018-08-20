Task:
Implement a function named factorial that has one parameter: an integer,n. It must return the value of n (i.e.,  factorial).

SOLUTION: 
```javascript
function factorial(n){
 for(var answer=1;n>0;n--){
    answer*=n;
  }
  return answer;
};
