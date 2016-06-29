# Gold Bootstrap 3.3.6
The latest version of Bootstrap based off the golden-ratio. A simple LESS/CSS style sheet is included that overrites some attributes of Bootstrap. The full version of Bootstrap is included (and untouched) with this package, including the CSS and JS files (i.e YOU DON'T NEED TO DOWNLOAD BOOTSTRAP AS WELL!)

## The Simple Setup (CSS)
Include `goldbootstrap.css` in your project. That's all. 

```html
// Core HTML
//...
<link rel="stylesheet" type="text/css" href="goldbootstrap/css/goldbootstrap.css"> // Add support for Gold Bootstrap
```

## The Simple Setup (LESS)

If you want to use LESS Preprocessors, include `gold-bootstrap.less` after your `bootstrap.less` import, and that's it.

```css
// Core LESS
//...
@import "goldbootstrap/less/goldbootstrap.less"; // Add support for Gold Bootstrap
```

## How to use it
Use any component from the regular [Bootstrap](http://getbootstrap.com). They're all included.

## What about GOLD Headings?
Extremely simple. Just use regular 'H1' through 'H6' HTML heading tags.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## What about the GOLD Grid?
Like you would do with any other Bootstrap column, simply use a set of `.col-gold-sm` and `.col-gold-lg` columns:

```html
<div class="row">
  <div class="col-gold-sm">...</div>
  <div class="col-gold-lg">...</div>
</div>
```
## How it works
Coming soon...

## Versioning
GOLD Bootstrap is always in sync with latest version of [Bootstrap](http://getbootstrap.com). If 'Bootstrap 9' comes out, we will be 'Gold Bootstrap 9' and so on.

## Changelog & Support

**06/30/16**

* Update to Bootstrap 3.3.6
* Added gold-template.html to get you started easier
* Added media queries to collapse Gold Columns on Mobile (anything under 991px)
* Fixed Gold Columns to extend to 100%
* Including Bootstrap Fonts Folder, so you truly don't need to download Boostrap
* Clarified Readme to state that Bootstrap is included, and you don't need to download it seperately

**06/16/15**

* Update to Bootstrap 3.3.5
* Added Changelog to this Readme
* Various Readme updates

**06/08/15**

* Swapped out seperate Boostrap JS files for compiled Boostrap.js

**04/24/15**

* Initial release using Bootstrap 3.3.4

## About the Author
[Kevin Rhodes](http://iamkevinrhodes.com) is a UX Designer from San Diego who loves Photoshop and front-end coding. He also loves his cat.

## License
&copy; Copyright 2015 Kevin Rhodes

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.