![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


## Exercise 1 - done with the lecturer

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/02_Lists_and_maps/01_Exercise_1`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**


Create a simple list containing 3 different colors. Set them as background colors for: `body`, `header` and `section` with `main-width` class.

Next, create a map containing 3 different width values. Set these widths for: `body`, `header` and `section` with `main-width` class.


## Exercise 2

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/02_Lists_and_maps/02_Exercise_2`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Create a map with five colors of your choice. Use it to set background color for the page, the text, and the footer.


## Exercise 3

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/02_Lists_and_maps/03_Exercise_3`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Create a map with 2 different width values, e.g.

```scss
$map: (
  min-width: 200px,
  max-width: 1000px
);
```

Next, using an appropriate function, create a **list of values from that map**.
Remember that in Sass, functions always return the result of the operation.
Assign the result of the appropriate function to a variable.
Next, set **the first element of the newly created list** as the width of the elements with `menu` class.

Use: [https://sass-lang.com/documentation/modules/map](https://sass-lang.com/documentation/modules/map).
