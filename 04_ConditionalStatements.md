# Conditional Statements

- `if`, `else if`, `else`, and `switch`
- Order of comparison statements is important
- Operators
    + Relational: `<` `<=` `>` `>=` `==` `===` `!=` `!==`
    + Logical: `&&` `||` `!`
    + Ternary: `variablename = (condition) ? value1:value2`

```javascript
let number1 = '4';
let number2 = 9;

let string = '';

if (number1 >= 96)
{
    string += 'Pitbull is ';
}
else if (number1 === 4 || !number2)
{
    string += 'Poodle is ';
}
else
{
    string += 'Beagle is ';
}

switch (number2) {
    case 3:
        string += 'the best ';
        break;
    case '-6':
        string += 'the sweetest ';
        break;
    case 9:
        string += 'the cuttest ';
    default:
        string += 'dog in world!';
}

fill(255, 90, 10);
textSize(25);
text(string, 10, height/2);
```

## Exercise - 4 Square

Your task is to split the canvas into four equal parts.

```
+-----+-----+
|     |     |
|     |     |
|     |     |
+-----+-----+
|     |     |
|     |     |
|     |     |
+-----+-----+
```

Using the **Relational and Logical Comparison** operators, determine where the mouse is in these squares. For whichever square the mouse is in, you should draw something.

If the mouse is in the top left square then draw something there.

```
+-----+-----+
|     |     |
| (-= |     |
|     |     |
+-----+-----+
|     |     |
|     |     |
|     |     |
+-----+-----+
```

If the mouse is in the bottom right square then draw something there.

```
+-----+-----+
|     |     |
|     |     |
|     |     |
+-----+-----+
|     |     |
|     |｡◕‿◕｡|
|     |     |
+-----+-----+
```

Etcetera

### Exercise Checklist

- [ ] [**core**] Made use of one or more relational operators
- [ ] [**core**] Made use of one or more logical operators
- [ ] Properly displays something in each of the four squares based off of the mouse's location

### Example

Here is a simple [4 square example](https://editor.p5js.org/Rudy.Castan/sketches/uLcN2PDff) drawing simple shapes in each region.
