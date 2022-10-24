![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


# Homework - Heading sizes

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `04_Day_2_-_Homework/01_Heading_sizes`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

Based on the map below, prepare a list with values only (using an appropriate Sass function).
Next, using an appropriate loop and list values, set sizes for headings from the `index.html` file, from the smallest to the biggest.

```scss
$font-sizes: (
 fs1: 100px,
 fs2: 50px,
 fs3: 6px
);
```


Use: [https://sass-lang.com/documentation/modules/map](https://sass-lang.com/documentation/modules/map)


# Homework - Units

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `04_Day_2_-_Homework/02_Units`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

In `index.html` you will find a section named `test_units`. Study it carefully. There are several elements within it. Set the font size of the `test_units` section to `30px`, add border, set its width to `25em` and height to `5em`.
Set the font size of the `header` element to `50%`.

Your task is to write a single CSS rule for span elements that will set their font size (using  `em` units) in such a way that:
* the first span was half the size of the font size defined for the `test_units` section,
* the second span was the same size as the font size defined for the `test_units` section.
