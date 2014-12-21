# Practical Machine Learning

This is the project for Coursera class Practical Machine Learning.


The output file is prerendered at [pml-project.html][1] The original source Rmarkdon file
is [pml-project.Rmd][2]

## Reporduction steps

The project dependencies, besides R, are [pandoc][3] and the following R packages:

  - caret
  - knitr
  - rmarkdown
  - doMC

and their respective dependecies.

For rendering the final project, `rmakdown` is used together with `pandoc`. To produce the final output, 
use the following sequence of R commands:

    library(rmarkdown)
    render("pml-project.Rmd", output_format="html")



[1]: http://alesk.github.io/pml-project/pml-project.html#/
[2]: https://github.com/alesk/pml-project/blob/master/pml-project.Rmd
[3]: http://johnmacfarlane.net/pandoc/
