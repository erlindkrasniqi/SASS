![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


## Exercise done with the lecturer

> ### Setup
> Modify `gulpfile.js` so that the `entryPath` variable points to:
> -  `03_Day_2/01_Inheritance/01_Placeholders`
>
> **Remember that after each change in `gulpfile.js` you should stop Gulp (`CTRL+C`) and run it again (`gulp`).**

### Exercise 1

In `index.html`find `section` element with `test-mixin` class. Style the elements within it according to their class descriptions (border, left side, etc.)
Next, using the sass placeholder - `%`, create a rule for clearfix. Clearfx should add `:before` and `:after` pseudo-classes to an appropriate element.
Use the `@extend` directive to extend individual elements with that placeholder.

---

## Exercises to do on your own

### Exercise 2

In `index.html` find `section` element with `container` class.
Within it, create three boxes representing: success, error and info.

![Placeholder](images/placeholder.jpg)

Style them using Sass. Try to use a **placeholder** in this exercise so as not to generate an additional CSS rule. Your HTML code should look like this:

```html
<div class="success">success</div>

<div class="error">error</div>

<div class="info">info</div>
```
