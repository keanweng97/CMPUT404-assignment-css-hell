Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

Part 1
====================

All 3 of our gutenberg documents contained inline CSS. 

To use our custom CSS file, we removed

```html
<style type="text/css">...</style>
```

and replaced it with:

```html
<link rel="stylesheet" href="gutenberg.css">
```

In `2.html`, there is a book cover included. We downloaded the complete webpage
using Firefox and the image is now served from `gutenberg/2_files/`.

To show our image captions theme,
we added a simple caption below the image:
```html
<figcaption>Book cover</figcaption>
```

References/Resouces
====================
 - CC-BY-ND License by Creative Commons from https://creativecommons.org/licenses/by-nd/2.0/ca/
 - Flexbox Guide by [Chris Coyier](https://css-tricks.com/author/chriscoyier/) from https://css-tricks.com/snippets/css/a-guide-to-flexbox/
  - Paper texture by Stephen Gilbert from https://www.transparenttextures.com/textured-paper.html 
 - Rainbow Background by w3schools from https://www.w3schools.com/css/css3_gradients.asp 

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


