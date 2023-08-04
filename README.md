# Project JavaScript Unit Tests

### This project consists of creating several functions to meet specific requirements and/or unit tests to ensure the implemented functions are correct.

* Designed by using JavaScript

## Description of created functions:

`average` (function): receives an `array` of `numbers` and returns the average of these numbers. If array is empty or no number `undefined` is returned.

`numbers` (test): function which receives an `array` and returns `true` if input parameters are type of `number` and returns `false` if opposite applies.

`vqv` (function): receives name and age as `strings` and returns template literals in following paragraph:
```
Oi, meu nome é Tunico!
Tenho 30 anos,
trabalho na Trybe e mando muito em programação!
#VQV!
```

`circle` (test): function which receives a circle radius and returns an `object` containing information like radius, area and circumference. If input parameter is not a `number`, `undefined` is returned.

`createStudent` (function): receives a name as input parameter and returns an `object` based of two `keys`:\
(1) `name`, representing input parameter and (2) `feedback`, containing a function which returns 'Eita pessoa boa!' when called.

`productDetails` (test): function which receives two `strings` of product names and returns an `array` with two `objects` and following product details:
```
[
  {
    name: 'Alcool gel'
    details: {
      productId: 'Alcool gel123'
    }
  },
  {
    name: 'Máscara'
    details: {
      productId: 'Máscara123'
    }
  }
]
```

`calculator` (function): receives two integer `numbers` and returns an `object` with following `keys`:\
(1) `sum`, which sums up the two values\
(2) `mult`, which multiply the values\
(3) `div`, which divide the values\
(4) `sub`, which substract the values


`arrayGenerator` (function): which converts `objects` in `arrays` by means of keys, values or entries. Function reveives two parameters, first one (1) a `string` which indicates the type of conversion and the second one (2) the proper `object` to be transformed.

