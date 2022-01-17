# Color

- RGB
    + Palette picker website: https://coolors.co/app or http://colormind.io
    + Convert hexadecimal to RGB: https://www.rapidtables.com/convert/color/hex-to-rgb.html
    + Color encyclopedia - https://www.colorhexa.com
- 0−255
- color functions [`background()`](https://p5js.org/ko/reference/#/p5/background), [`fill()`](https://p5js.org/ko/reference/#/p5/fill), and [`stroke()`](https://p5js.org/ko/reference/#/p5/stroke)
- Specifying Color For these functions
    + `background('#FF043B');` ⟵ Hexadecimal color codes
    + `background('SkyBlue');` ⟵ CSS Color Names
    + `background(120);` ⟵ Grey scale
    + `background(120, 0, 35);` ⟵ RGB
    + Alpha -> 255 is opaque and 0 is fully transparent
        - `fill(120, 0, 35, 127);` ⟵ RGBA
        - `stroke(120, 127);` ⟵ Grey scale with alpha
- Color Settings are preserved
    + Until `fill()` is called again all subsequent draw calls will have the same fill color
- [`noFill()`](https://p5js.org/ko/reference/#/p5/noFill), [`noStroke()`](https://p5js.org/ko/reference/#/p5/noStroke) and [`strokeWeight()`](https://p5js.org/ko/reference/#/p5/strokeWeight)

## Exercise - Draw a fictional character

Your task is to use the Shape Property and Color functions to draw a picture of one of your favorite fictional characters.

### Requirements

You must use each of the following at least one time

- Call a color function with 1 argument
- Call a color function with 2 arguments
- Call a color function with 3 arguments
- Call a color function with 4 arguments
- Draw a shape with no fill
- Draw a shape with no outline
- strokeWeight()

Note: You don't have to use all of these functions to represent the dog. You may add decorations in order to fulfill this requirement.

### Exercise Checklist

- [ ] [**core**] Drew a picture of one of their favorite fictional characters
- [ ] Called a color function with 1 argument
- [ ] Called a color function with 2 argument
- [ ] Called a color function with 3 argument
- [ ] Called a color function with 4 argument
- [ ] Drew a shape with no fill
- [ ] Drew a shape with no outline
- [ ] Used strokeWeight()

### Example

Checkout [Kirby](https://editor.p5js.org/Rudy.Castan/sketches/ym2bgkJSm)
