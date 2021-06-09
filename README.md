# NYT Covid Analysis

Sample project that I completed. Interactive shiny application that uses data from the public New York Times Repository.

Although we are able to update the data through the submodule in our repository by sourcing the `import.r` script, the published shiny application has data through June 7, 2021.

Here is the link to the published shiny application:

https://hunternosek.shinyapps.io/nyt-covid-analysis/ 

## Prerequisites

### R Packages

The following code was used to install necessary packages:

```{r eval = FALSE}
install.packages(c(
  "rmdformats",
  "tidyverse",
  "reactable",
  "mapview"
))
```

We also need the `urbnmapr` package for the map, so this code was used for that:
```{r eval = FALSE}
install.packages("devtools")
devtools::install_github("UrbanInstitute/urbnmapr")
```

