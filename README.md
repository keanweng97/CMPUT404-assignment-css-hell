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

References
====================

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


