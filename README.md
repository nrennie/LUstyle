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

## Examples

### CHICAS Data Visualisation Workshop Slides

GitHub: [github.com/nrennie/chicas-data-viz-workshop](https://github.com/nrennie/chicas-data-viz-workshop)

Slides: [nrennie.github.io/chicas-data-viz-workshop](https://nrennie.github.io/chicas-data-viz-workshop/#/title-slide)

### R/Pharma {tidymodels} Workshop Slides

GitHub: [github.com/nrennie/r-pharma-2023-tidymodels](https://github.com/nrennie/r-pharma-2023-tidymodels)

Slides: [nrennie.github.io/r-pharma-2023-tidymodels](https://nrennie.github.io/r-pharma-2023-tidymodels/#/title-slide)

### Teaching with webR Slides

GitHub: [github.com/nrennie/teaching-with-webR](https://github.com/nrennie/teaching-with-webR)

Slides: [teaching-with-webr.netlify.app/](https://teaching-with-webr.netlify.app/#/title-slide)
