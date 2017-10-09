# NeuRRoStat
As an *R master* once said:
> \[...]: anything that can be automated, should be automated. Do as little as possible by hand. Do as much as possible with functions. \[Hadley Wickham]

This package is an ongoing effort/development to gather subroutines (i.e. functions) that we often use for simulations, analyses, etc. In the long run, we hope to:
  * reduce errors occuring from re-creating functions for each project
  * work more efficiently

# Requirements
To install the package directly from Github, one needs to have *devtools* installed. In **R** run:
```{r}
library(devtools)
```

If not installed, run:
```{r}
install.packages('devtools')
```

# Install the package

To install the stable branch, run:
```{r}
devtools::install_github("NeuroStat/NeuRRoStat", ref = "master")
```

