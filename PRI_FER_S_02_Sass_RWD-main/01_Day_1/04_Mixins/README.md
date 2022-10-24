![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `01_Day_1/04_Mixins/01_Exercise_1`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

## Exercise 1 - done with the lecturer

In `index.html` find a `section` element with `test-mixin` class. Style the elements within according to their class descriptions (border, left side, etc.)
Next, create a simple mixin that will add `:before` and `:after` pseudo-elements to an appropriate element. Name the mixin **clearfix**.


> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `01_Day_1/04_Mixins/02_Exercise_2`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

## Exercise 2

Create a mixin that will set font size for the `header` element based on the `$font` parameter passed to it. Additionally, it should set `border-radius` to `5px`.


> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `01_Day_1/04_Mixins/03_Exercise_3`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**


## Exercise 3

Create a mixin named `dialogBox` that will take two parameters - color ($backgroundColor) and box width ($width). Its task will be to set styles for the element with `dialog` class.

```
  width: $width;
  padding: 10px;
  background: $backgroundColor;
  border: 1px solid black;
  margin: 40px auto;
```

In the mixin, add a `:after` pseudo-element that will create a 10x10px square that decorates the box. The final effect should be the following:

![Dialog](images/dialog.png)

Test your code for `green` and `lightgray` background, and also test it with random widths.
