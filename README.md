# calotriton_respirometry

Respirometry tests analysis in Calotriton asper newts from different altitutes acclimated to distinct temperatures


## Data analysis

Samples were analysed together and the code used can be found in the Rmd files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[alberdilab.github.io/calotriton_respirometry](https://alberdilab.github.io/calotriton_respirometry)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
