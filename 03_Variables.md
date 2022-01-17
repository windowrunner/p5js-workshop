# Variables

A variable is a way to store values. To use a variable, we must both declare it to let the program know about the variable and then assign it to let the program know what value we are storing in the variable. Here's how we would declare a variable named "xPosition":

```javascript
let xPosition;
```

Now, we can assign xPosition to hold the value 10:

```javascript
xPosition = 10;
```

If we want to _(and we often do!)_ we can declare and assign in one statement:

```javascript
let xPosition = 10;
```

If, for some reason, we want to change the value of a variable later, we can re-assign it:

```javascript
let xPosition = 10;

// some time later ...

xPosition = 20;
```

If we don't plan on changing the value of the variable but wish to keep it **constant** then we can declare it as such:
```javascript
const BUBBLE_WIDTH = 100; // can't change BUBBLE_WIDTH to store any other value now
```

Re-assignment can be useful when we want to animate our drawings.

How can we pick names for our variables? For variables in JavaScript, follow these rules:

Variable names can begin with letters, or the symbols `$` or `_`. They can only contain letters, numbers, `$` and `_`. They cannot begin with a number. `myVariable`, `leaf_1`, and `$money3` are all examples of valid variable names.

Variable names are case sensitive, which means that `xPosition` is different from `xposition`, so make sure you are consistent.

Variable names can't be the same as existing variable names, and there are a lot in our p5js programming environment. If you ever see an error pop up like "Read only!", try changing your variable name.

Variable names should be clear and meaningful; for example, instead of `ts`, use `toothSize`. Variable names should use camel case for multiple words, like `toothSize` instead of `toothsize` or you could try snake case `tooth_size`.

## Mapping range values

- Reactive Animation
- [`map()`](https://p5js.org/ko/reference/#/p5/map)
- Change the background color based off of the mouse position.
    + Map the mouseX range of vales, (0−width), to the backgrounds red channel, 0−255.
    + Map the mouseX range of vales, (width−0), to the backgrounds green channel, 240−100.
    + Map the mouseY range of vales, (0−height), to the backgrounds blue channel, 50−200.

## Exercise - Animate an Object

Your task is to create your own variables to animate an object. Animate it's position, size, fill color, stroke size, and stroke color.

### Requirements

- Create your own variables to keep track of the objects position, size, fill color, stroke size and stroke color
- Update all of your variables in `draw()`
- Reset all your variables to their initial state when the mouse is pressed
	- Utilize `function mousePressed()`
- Randomize your variables when any keyboard button is pressed.
	- Utilize `function keyPressed()`

### Exercise Checklist

- [ ] [**core**] Declared, initialized and used your own variables to animate position, size, fill color, stroke size and stroke color
- [ ] Resets to the initial state when any mouse button is pressed
- [ ] Resets to a random state when any keyboard button is pressed

### Example

Here is an example that changes all the [properties of a circle.](https://editor.p5js.org/Rudy.Castan/sketches/cgeFWv47P)
