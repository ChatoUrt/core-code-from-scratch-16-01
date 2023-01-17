# core-code-from-scratch-16-01

## ---If, else and ternary operator test---

* [Test](https://www.codewars.com/kata/57202aefe8d6c514300001fd/train/javascript)

Solution / /
``` javascript
function saleHotdogs(n){
  if (n < 5) return n * 100
  else if (n >= 5 && n < 10) return n * 95
  else  return n * 90;
}


/* --- also works ---

  return n * (n < 5 ? 100 : n < 10 ? 95 : 90);

*/ // --- also works ---
```

---
## ---
* [Test](https://www.codewars.com/kata/572059afc2f4612825000d8a/train/javascript)

Solution / /

``` javascript
function howManydays(month){
  var days;
  switch (month){
      case 4:
      case 6:
      case 9:
      case 11:
        days = 30;
        break;
      case 2:
        days = 28;
        break;
      default:
        days = 31;
  }
  return days;
}
```

---
## ---Basic Calculator---
* [Test](https://www.codewars.com/kata/5296455e4fe0cdf2e000059f/train/javascript)

Solution / /

``` javascript
function calculate(a, ops, b) {
  var t ;
  switch(ops){
      case "+":
        t = +a + +b;
      break;
      case "-":
        t = +a - +b;
      break;
      case "*":
        t = +a * +b;
      break;
      case "/":
        t = +a / +b;
        if (b == 0) return t = null
      break;
      default:
        t = null;
  }
  return t
}
```

---
## ---Knowledge Base---
1. [JavaScript if, else, and else if](https://www.w3schools.com/js/js_if_else.asp)<br>
1.1. [If ... else](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)<br>
1.2. [Conditionals (ternary) operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
2. [JS switch statement](https://www.w3schools.com/js/js_switch.asp)<br>
2.1. [Switch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)<br>
2.2. [JavaScript switch case: Ejemplo de sentencias switch en JS](https://www.freecodecamp.org/espanol/news/javascript-switch-case-ejemplo-de-sentencias-switch-en-js/)
