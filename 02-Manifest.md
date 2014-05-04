#Manifest

A commit *can* contain a `manifest.yml` file. This file is in
the [YAML](http://en.wikipedia.org/wiki/YAML) format. You can
configure and customize most of the generated output, such as
page order, title, formats, title, etc.

##Options

`author` String

The author of the book.


`title` String

The title of the book.


`pages` Array of Strings

An array of relative paths.  The book will be assembled in the order of pages given here.

`formats` Array of Strings

An array of formats that should be generated.  Deafults to *html, pdf, epub, mobi


`table_of_contents` Boolean

Defualts to *true*.  Enabling will generate a table of contents and append it to the beginning of the book.  Headings are used to generate the TOC.


`include_before_body` String

A relative path to the file that should be included before each pages body.

`include_after_body` String

A relative path to the file that should be included after each pages body.
