# Expression Parser

Top down parser with left recursion for parsing complex expressions.

## Following operators allowed

  * Numbers - Int only!(for now)
  * Normal Operators - +, -, *, /
  * If/Else - if('value' <|>|= 'value', 'whenTrue', 'whenFalse')
  * Braces - ()
  * Log - log(number, base)
  * Natural Logarithm - ln(number)

### Example expression

```
98+if(log(56*3,32) > 98, 845*32,ln(37))
```

### Prerequisites

You need to have g++ installed. 

### Installing

Clone repo

```
git clone https://github.com/ivo96/tree-parser.git
```

Change permissions

```
chmod +x ./compile.bash
```

Compile

```
./compile.bash
```

Run the executable

```
./bin/calculator  
```
