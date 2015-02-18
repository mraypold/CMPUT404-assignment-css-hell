Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git


Part I
=================

Chosen Gutenberg Documents:

* [Peter Pan](http://www.gutenberg.org/files/16/16-h/16-h.htm) by J. M. Barrie
* [A Tale of Two Cities](http://www.gutenberg.org/files/98/98-h/98-h.htm) by Charles Dickens
* [The Adventures of Sherlock Holmes](http://www.gutenberg.org/files/1661/1661-h/1661-h.htm) by Arthur Conan Doyle

HTML Modifications

* I added specific `<div>` and `<span>` tags for inline titles, copyright, and licensing
* Added chapter classes for each chapter.
* In general, I tried to use existing classes in the Gutenberg documents instead of making my own. For instance, using the existing toc class for table of contents.
* Remove some custom spans in *A Tale of Two Cities* that interferred with my css. For instance span tags that made the first character of a paragraph in a chapter 4em.

Style Modifications

* Added custom google fonts for titles and first letter of chapters.
* Text now takes up the entire length of paragraph within margins.
* Increased margin size.
* Made a title page and styled it to look like a book.
* License at bottom of document stands out in red.
* Changed some background colours.
* Necessary changes from requirements.org (header, img, etc...)

Part II
=================

Made use of bootstrap and some css/html code provided by others to make the webpage look more professional. I have included my first disasterous attempt in the throwaway folder for comparison.

Both HTML files are the same when running `diff -w -B index_nice.html index_ugly.html > diff.txt`.

Sources Specific to Part II:

* Help with [sidebar layout](http://stackoverflow.com/questions/18147887/html-layout-adding-sidebar-column-to-existing-site)
* Used some code from the [Simple Sidebar](http://startbootstrap.com/template-overviews/simple-sidebar/) template by start boostrap. Modifications made to coloring and spacing to match existing bootstrap theme and positioning. Simple Sidebar licensed under [Apache v2.0](https://github.com/IronSummitMedia/startbootstrap/blob/gh-pages/LICENSE)
* Further assistance with sidebar from [Jonathan Briehl](http://www.jonathanbriehl.com/2014/01/17/vertical-menu-for-bootstrap-3/)
* Stary background pattern css by [Lea Verou](http://lea.verou.me/css3patterns/#starry-night)
* Overwrote some Bootstrap classes to change the styling for the ugly theme.

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the [CC-BY-SA
4.0 unported license](https://creativecommons.org/licenses/by-sa/4.0/legalcode). Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Existing licenses maintained by Michael Raypold

External Libraries and Sources
=================
* Made use of google fonts [Open Sans](https://www.google.com/fonts/#QuickUsePlace:quickUse), [Berkshire Swash](http://www.google.com/fonts#UsePlace:use/Collection:Berkshire+Swash), and [Courgette](http://www.google.com/fonts/specimen/Courgette)
