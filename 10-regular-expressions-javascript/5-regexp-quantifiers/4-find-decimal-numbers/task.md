# Найдите десятичные числа

Создайте регэксп, который ищет все числа, в том числе и с десятичной точкой, в том числе и отрицательные.

Пример использования:

```js
var re = /* ваш регэксп */

var str = "-1.5 0 2 -123.4.";

alert( str.match(re) );   // -1.5, 0, 2, -123.4
```