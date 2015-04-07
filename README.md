# Gold Bootstrap
The latest version of Bootstrap based off the golden-ratio.

## The Simple Setup
Include `goldbootstrap.css` in your project. That's all. The most recent version of Bootstrap is included.

```sass
// Core CSS
//...
@import "golden-bootstrap/golden-bootstrap.scss"; // Add support for Gold Bootstrap
```

If you want to use LESS or SASS Preprocessors, include `gold-bootstrap.less` in `bootstrap.less` or `goldbootstrap.scss` in `bootstrap.scss`, and that's it.

```sass
// Core CSS
//...
@import "golden-bootstrap/golden-bootstrap.scss"; // Add support for Golden Bootstrap
```

## Using the GOLD Headings
Extremely simple. Just use regular H1-H6 HTML heading tags.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Using the GOLD GRID
Like you would do with any other Bootstrap column, simply use a set of `.col-gold-sm` and `.col-gold-lg` columns:

```html
<div class="row">
  <div class="col-gold-sm">...</div>
  <div class="col-gold-lg">...</div>
</div>
```

## Using the GOLD Helpers
Any time your need to add padding or margins on things, use the following classes. This helps maintain good vertical rythym.

```html
<div class="row">
  <div class="col-gold-sm">...</div>
  <div class="col-gold-lg">...</div>
</div>
```


## How it works
“Two quantities are in the golden ratio if the ratio of the sum of the quantities to the larger quantity is equal to the ratio of the larger quantity to the smaller one” ([source](http://en.wikipedia.org/wiki/Golden_ratio)). Under the hood it looks like this: