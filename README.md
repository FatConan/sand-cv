# Sand CV 

Sand CV is an example project that uses the static site generator [Sand](https://github.com/FatConan/sand) to build an 
HTML CV from a markdown document. This example project uses a LaTeX-style CSS to make the document look 
presentable and as a means of demonstrating what can be achieved.

## Prerequisites

This project requires Python 3.x and the [Sand](https://github.com/FatConan/sand) tool to be installed.

## How to use it

You may replace the content of `cv.md` with your own CV in markdown. You can run `sand . --serve` from within the
project's folder to render the CV as HTML and start it running on a debug server at [http://localhoist:9000].

Once you're happy the content of the output folder may be hosted at the webserver of your choice to provide online access
or you can use your browser's print to PDF function to capture the CV from your debug server as a PDF.

By playing around with the project you can tweak the CSS, or replace it entirely with something of your own choosing. 
In other projects I've also added Sand plugins to extend the markdown functionality to add custom elements. 

## Why?

I use Sand to generate all of my websites (and I use it to generate an HTML version of my own CV) and thought it might 
be of use.