# `140` modulo

## 馃摑 Instrucciones:

1. Escribe una funci贸n llamada `m贸dulo`.

Dados 2 n煤meros, `m贸dulo` retorna el resto despu茅s de dividir `num1` entre `num2`.

Debe comportarse como se describe en la documentaci贸n can贸nica (MDN) para el operador de JavaScript restante:

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Remainder_()

## :bulb: Pista:

* NO use el operador de m贸dulo incorporado real (tambi茅n conocido como "resto") (`%`) en su implementaci贸n.

* `0 % ANYNUMBER = 0`.

* `ANYNUMBER % 0 = NaN`.

* Si cualquiera de los operandores es `NaN`, entonces el resultado es `NaN`.

* El m贸dulo siempre devuelve el signo del primer n煤mero.

```Js
var output = modulo(25, 4);
console.log(output); // --> 1
```