#Manifest

A commit *can* contain a `manifest.yml` file. This file is in
the [YAML](http://en.wikipedia.org/wiki/YAML) format. You can
configure and customize most of the generated output, such as
page order, title, formats, title, etc.

##Options

| Option             | Default        | Description |
|--------------------|----------------|-------------|
| author             | null           | *string* - author of the book|   
| title              | null           | *string* - title of your book|
| pages              | null           | *array* - of relative paths to your pages | 
| formats            | pdf,html,epub,mobi| *array* - of output formats |
| stylesheet         | null   | *string* - relative path to the books stylesheet|
| table_of_contents  | true   | *boolean* - appends the *TOC* above the contents of the book |
| include_in_header  | null   | *string* - relative path to a file that will be appended to the header|
| include_before_body| null   | *string* - relative path to a file that will be appended before the body of each page|
| include_after_body| null   | *string* - relative path to a file that will be appended after the body of each page|