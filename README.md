# smalldoc

Small Web Documentation System

Smalldoc is a script that generates static HTML pages with a table of contents, from source files that are written in Markdown syntax.

Smalldoc is simple, and is suitable for small sites : all files are in the same directory.

## Example

An example generated with Smalldoc is <a href="http://goeb.github.io/smit/">Smit</a>.

## Requirements:

- shell
- pandoc
- GNU make

## Getting Started

An example is provided. Simply type `make` to build it.

Then browse to example/index.html to see the result.



## How it works

Input files of the example:

    header.html
    footer.html
    index.md
    documentation.md
    etc.

Ouput files:

    index.html
    documentation.html
    etc.

The generated HTML pages consists in:

    a header (taken from header.html where __TITLE__ has been replaced)
    a table of contents (where the entries are taken from the other .md files)
    the content of the page
    a footer (taken from footer.html)
    

