**Recursive Drawing** is an exploration of user interface ideas towards the development of a spatially-oriented programming environment.

 * [Fast tutorial video](http://recursivedrawing.com/)
 * [Start Drawing!](http://recursivedrawing.com/draw.html)

## Installation from Github
By terminal
```
cd yourFolder
git clone https://github.com/electronicwhisper/recursive-drawing.git
```
To start drawing point your browser at the `yourFolder/recursive-drawing/index.html`.


## Complete list of instructions

Textual instructions (if you don't want to  [watch the demo video](http://recursivedrawing.com/)):

 * The left column is the shapes library. The center area is the canvas/workspace. The right area is an outline view of the shapes in the canvas.

 * To add a shape to the canvas, drag your mouse from the shape in the shape library to the workspace.

 * To move a shape, drag inside it, when the whole shape is highlighted red.

 * To resize and rotate a shape, drag the edge of it, when it is outlined red.

 * To delete a shape on the canvas, right-click it and choose Delete Shape. (You currently cannot delete shapes directly from the outline, nor can you delete shapes from the shape library.)

 * To resize a shape non-uniformly or add skew, hold shift while dragging its outline. You can use this to make line segments and rhombuses, among other things.

    * Click the + button in the left column to start editing a new shape.

    * Remember that you can add any shape to the canvas by dragging it from the shape library. This also applies to shapes you create yourself.

    * Click on any shape in the shape library (except for the starting circle and square) to edit it in the canvas.

    * You can see the thumbnail of what's in the canvas in the current shape in the shape library. You can also see the shapes your shape is composed of in the outline. Everything is updated live.

 * To pan across the canvas, drag outside of any shape, in the white area. To zoom into or out from the canvas, scroll with the mouse wheel while pointing inside the canvas.

 * You can drag even the shape you are currently editing from the shape library into the canvas. That is what makes this recursive drawing rather than merely nested drawing. You will see the current shape repeated relative to itself. (You might call the shape inside itself a "recursive shape instance".)

 * You can move, rotate, and resize a recursive shape instance to change its repetition pattern. For instance, if you resize the recursive shape instance to be smaller, you will see a line of recursive shapes shrinking forever. If you edit one of the repetitions of a shape, it will edit the whole pattern.

 * You can go back and edit a sub-shape, and every shape including that shape will update live.

##Examples

You can trying your hand on some *[Sierpinski carpet](https://en.wikipedia.org/wiki/Sierpinski_carpet)* and *pseudo-dragon curve*... After some practice you will get!  **[Try these ones](http://imgur.com/a/EneFC)**.

Here's a *[Sierpinski triangle](https://en.wikipedia.org/wiki/Sierpinski_triangle)*,

> ![http://i.imgur.com/tMbrj.png](http://i.imgur.com/tMbrj.png)

it has been drawn by @bryogenic, and he noticed some difficulty to achieve without precision snapping tools; use some object at screen as "analogic ruler".

If you don't know what to draw, try drawing one of these: [any kind of fractal tree](https://www.google.com/search?q=fractal+tree&tbm=isch...), [Koch snowflake](http://en.wikipedia.org/wiki/Koch_snowflake),  [Sierpinski triangle](http://en.wikipedia.org/wiki/Sierpinski_triangle),  [Sierpinski carpet](http://en.wikipedia.org/wiki/Sierpinski_carpet), or [any other fractal](http://en.wikipedia.org/wiki/List_of_fractals).

## License

This material is licensed by its maintainers under the Public Domain Dedication
and License.

...
