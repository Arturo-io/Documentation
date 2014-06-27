#Manifest

A commit *can* contain a `manifest.yml` file. This file is in
the [YAML](http://en.wikipedia.org/wiki/YAML) format. You can
configure and customize most of the generated output, such as
page order, title, formats, title, etc.  An example `manifest.yml` can be found in this documentations [repo](https://github.com/Arturo-io/Documentation/blob/master/manifest.yml).

##Options
`css` String

The relative path to a stylesheet which is applied to *most* formats.


`author` String

The author of the book.


`title` String

The title of the book.


`pages` Array of Strings

An array of relative paths.  The book will be assembled in the order of pages given here.


`formats` Array of Strings

An array of formats that should be generated. Defaults to *html, pdf, epub, mobi*


`table_of_contents` Boolean

Defaults to *true*.  Enabling will generate a table of contents and append it to the beginning of the book.  Headings are used to generate the TOC.


`include_before_body` String

A relative path to the file that should be included before each pages body.


`include_after_body` String

A relative path to the file that should be included after each pages body.
