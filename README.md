---
title: "Viridis Color Palettes"
---

R Markdown enables you to weave together content and executable code into a finished document. To learn more about R Markdown see [rmarkdown.rstudio.org](https://rmarkdown.rstudio.com/). This template uses R Markdown to demonstrate the color palettes of R's Viridis package in three mediums:

-   as an HTML, PDF, or Word document in `colors_document.Rmd`
-   as a slide deck in `colors_presentation.Rmd`
-   as a web page with interactive Shiny components in `colors_app.Rmd`

# Previewing

## To preview the document

1.  Open the file `colors_document.Rmd`.
2.  Then click the Knit button that will appear above the opened file. This will display the document as an HTML file.
3.  To display the document as a pdf or MS Word file, click the drop down menu to the left of the Knit icon and select one of:
    a.  Knit to PDF
    b.  Knit to Word

## To preview the presentation

1.  Open the file `colors_presentation.Rmd`.
2.  Then click the Knit button that will appear above the opened file. This will display the document as an ioslides HTML slide deck, which can be presented with any web browser.
3.  To display the presentation as a Slidy (HTML), beamer (PDF), or MS PowerPoint slide deck, click the drop down menu to the left of the Knit icon and select one of:
    a.  Knit to HTML (Slidy)
    b.  Knit to PDF (Beamer)
    c.  Knit to PowerPoint

## To preview the interactive document with Shiny components

1.  Open the file `colors_app.Rmd`.
2.  Then click the Run Document button that will appear above the opened file. Because the file contains the YAML line `runtime: shiny`, R Markdown will run the file as an interactive [Shiny](https://shiny.posit.co/) app.

# Publishing

## To publish these documents to Posit Cloud

1.  Open the document.
2.  Click the blue publish icon that will appear to the far right above the document.
3.  Complete and submit the dialog that appears.

Your published output will appear in another browser tab, where you can interact with it.

It will also get added as a new content item to Your Workspace. You can see it listed there by clicking the Your Workspace link in the header.

## To publish to other hosting services

In addition to publishing content to Cloud, you can also publish to these other hosting services:

1.  [Posit Connect](https://posit.co/products/enterprise/connect/)
2.  [shinyapps.io](https://www.shinyapps.io/)
3.  [RPubs](https://rpubs.com/)

Consult the documentation for those services for details on how to publish to them.

### Packages

This template includes the following installed packages, among others:

-   [shiny](https://shiny.posit.co/)
-   [quarto](https://quarto.org/)
-   [tidyverse](https://tidyverse.tidyverse.org/) (meta-package)
-   [ggplot2](https://ggplot2.tidyverse.org/)
-   [dplyr](https://dplyr.tidyverse.org/)
-   [tidyr](https://tidyr.tidyverse.org/)
-   [readr](https://readr.tidyverse.org/)
-   [purrr](https://purrr.tidyverse.org/)
-   [tibble](https://tibble.tidyverse.org/)
-   [stringr](https://stringr.tidyverse.org/)
-   [forcats](https://forcats.tidyverse.org/)
-   [tidyr](https://tidyr.tidyverse.org/)
-   [here](https://here.r-lib.org/)
-   [patchwork](https://patchwork.data-imaginist.com/articles/patchwork.html)
-   [viridis](https://sjmgarnier.github.io/viridis/)

Install additional packages as desired with `install.packages()`.
