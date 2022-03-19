# Tayan Bostybaev

### Contact information
**Phone:** +77012620792 (Whatsapp)
**E-mail:** bostybaev@gmail.com

### Code example
**Find divisors from Codewars**

*Create a function named divisors/Divisors that takes an integer n > 1 and returns an array with all of the integer's divisors(except for 1 and the number itself), from smallest to largest. If the number is prime return the string '(integer) is prime' (null in C#) (use Either String a in Haskell and Result<Vec<u32>, String> in Rust).*
```JavaScript
function divisors(integer) {
  let arr = [];
  if(integer > 1) {
    for(let i = 2; i < integer; i++){
      if (integer % i == 0){
        
        arr.push(i);
      }
      
    }
    
  }
  if(arr.length == 0){
     return `${integer} is prime`;
  }
      
  return arr;
};
```
