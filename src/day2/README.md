# Bitwise Operations and File IO

#### AND, OR, XOR

truth table:

 A | B | A AND B
:-:|:-:|:------:
 0 | 0 |    0
 0 | 1 |    0
 1 | 0 |    0
 1 | 1 |    1

how boolean AND works.

examples, doing each bit pair at a time in isolation:

```
  01011010
& 10101111
----------
  00001010
```

some more examples with OR.

Show the C operators:

Operation | Bitwise Operator | Boolean Operator
:--------:|:----------------:|:---------------:
   OR     |        `\|`      |      `\|\|`
   AND    |        `&`       |       `&&`
   XOR    |        `^`       |       none
   NOT    |        `~`       |       `!`

 A | B | A OR B
:-:|:-:|:-----:
 0 | 0 |   0
 0 | 1 |   1
 1 | 0 |   1
 1 | 1 |   1

Exclusive-OR means that one or the other must be true, but not both.

 A | B | A XOR B
:-:|:-:|:------:
 0 | 0 |    0
 0 | 1 |    1
 1 | 0 |    1
 1 | 1 |    0

 A | NOT A
:-:|:----:
 0 |  1
 1 |  0
