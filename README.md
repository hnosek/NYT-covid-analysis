# NYT Covid Analysis

Sample project that I completed. Interactive shiny application that uses data from the public New York Times Repository.

* https://github.com/nytimes/covid-19-data/tree/b3e4e4ca9c2fa82b36da2082dffaa42e58ec082f

Although we are able to update the data through the submodule in our repository by sourcing the `import.r` script, the published shiny application has data through June 7, 2021.

Code used to build the shiny application are in the `ui.r` and `server.r` files.

## Application

Here is the link to the published shiny application:

* https://hunternosek.shinyapps.io/nyt-covid-analysis/ 

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

