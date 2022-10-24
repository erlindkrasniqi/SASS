![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


## Exercise 1 - done with the lecturer

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/03_Logic_in_SASS/01_Exercise_1`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Write 6 headers on the page, from **h1** to **h6**.
In a variable, save line height and basic font size for `h1`.

Style the headers in such a way that their size changes based on the defined font size. Use loops and interpolation.

Calculate properly the size of each header, remember about their hierarchy (**h1** should be the biggest).

Set different colors for the headers.

> Use the `sass:color` module `color.mix` function to mix two colors: `tomato` and `cornflowerblue` in appropriate proportions. The higher the header, the higher the percentage of color mixing, e.g.:
>
> h1: `color.mix(tomato, cornflowerblue, 10%)`  
> h2: `color.mix(tomato, cornflowerblue, 20%)`  
> etc.
>
> Documentation: [https://sass-lang.com/documentation/modules/color#mix](https://sass-lang.com/documentation/modules/color#mix)


## Exercise 2

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/03_Logic_in_SASS/02_Exercise_2`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Write a mixin named `drawItem` that will take two arguments - shape to draw, and its background color.

* If the shape is `circle` - it will create a circle with 100px diameter.
* If the shape is `rectangle` - it will create a 200px x 200px square.

Add the mixin to the `div` with `draw-container` class.


## Exercise 3

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/03_Logic_in_SASS/03_Exercise_3`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Using a loop, set border color for ten containers, e.g. `div` elements. The color should be orange for the even containers, and blue for the odd ones.

Give the containers **classes** from ```block_1``` to ```block_10```. Use a loop.
