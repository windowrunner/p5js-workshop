# Loops

We rarely do something once. Therefore, programming languages provide convenient ways of doing something several times. This is called _repetition_, _looping_, or when you do something to a series of elements — _iteration_.

Let's consider a program that produces the following:

```
0   0
1   1
2   4
3   9
4   16
 ...
98  9604
99  9801
```

Calculation and printing of a list of squares
Each line is a number followed by a “tab” character ('\t'), followed by the square of the number.

A javascript version looks like this;

```js
let i = 0;
while(i<100)
{
    console.log(i+'\t'+i*i);
    ++i;
}
```

When looping there are three things we need to think about.

1. What is the initial starting point?
2. What is the ending point?
3. What are we repeating?

In the example above the answer to these questions are:

1. We start with 0
2. We see if we have reached 100, and if so we are finished
3. Otherwise, we print the number and its square separated by a tab ('\t'), increase the number, and try again.

These three questions are so often used that programming languages have a special syntax for it, the `for` loop.

We could redo the example as:

```js
for(var i = 0; i < 100; ++i){
    console.log(i+'\t'+i*i);
}
```

You can read it like the following:

```
for( initial starting point ; ending point ; simple increment ){
repeated logic
}
```

## Exercise - Draw Grid lines

Write a sketch that displays a sequence of horizontal and vertical lines to create a grid spaced out by **50 pixels**. Also draw the values of the x and y values. At each cross section draw a small circle.

```
o---o---o---o---o---o---o---o---o---o---o---o->
|  0| 50|100|150|200|250|300|350|400|450|500|  
o---o---o---o---o---o---o---o---o---o---o---o->
| 50|   |   |   |   |   |   |   |   |   |   |  
o---o---o---o---o---o---o---o---o---o---o---o->
|100|   |   |   |   |   |   |   |   |   |   |  
o---o---o---o---o---o---o---o---o---o---o---o->
|150|   |   |   |   |   |   |   |   |   |   |  
o---o---o---o---o---o---o---o---o---o---o---o->
|200|   |   |   |   |   |   |   |   |   |   |  
o---o---o---o---o---o---o---o---o---o---o---o->
|250|   |   |   |   |   |   |   |   |   |   |  
v   v   v   v   v   v   v   v   v   v   v   v  
```


### Exercise Checklist

- [ ] [**core**] Utilizes 1 or more for loops
- [ ] [**core**] Utilizes 1 or more while loops
- [ ] Properly display grid of lines
- [ ] Properly display x anf y values
- [ ] Display a small circle at each cross section

### Example

Here is a [grid example.](https://editor.p5js.org/Rudy.Castan/sketches/3-d8N6T7C)

