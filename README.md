# Lancaster University Quarto Theme

This repository contains a (personal) template for Lancaster University Quarto documents. It includes an extension that can style revealjs slides, PDFs, and HTML documents.

## Installation and use

To install the Quarto extension to the current directory:

``` bash
quarto install extension nrennie/LUstyle
```

To install the Quarto extension and copy the template file to the current directory:

``` bash
quarto use template nrennie/LUstyle
```

This will copy a template file for revealjs slides.

If you want to use the PDF template instead, set:

``` yaml
format: LUstyle-pdf
```

or for HTML documents:

``` yaml
format: LUstyle-html
```