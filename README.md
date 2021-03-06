# cati: Communities Assembly by Traits: Individuals and beyond

---
## A R package to detect communities assembly processes by functionnal traits

The package is described in *Ecography*: **[cati: an R package using functional traits to detect and quantify
multi-level community assembly processes](http://onlinelibrary.wiley.com/doi/10.1111/ecog.01433/pdf)**. 


### Install the latest versions of all dependencies from CRAN:

```r
install.packages(c("devtools", "e1071", "mice", "rasterVis", "hypervolume", "FD", "geometry", "vegan", "nlme", "ade4", "ape"))
```
### Install cati's current development version from Github:

```r
devtools::install_github("adrientaudiere/cati/pkg/cati")
```

### Install cati's cran version:
```r
install.packages("cati")
```

### Attach the package and you are ready to start:
```r
library(cati)
```

---
There's a **[tutorial](https://github.com/adrientaudiere/cati/blob/Package-cati/Documentation/vignette_Darwin_finches/vignette.pdf)** which illustrate the cati package using Darwin finches data.

---
How to cite?

"Taudiere, A. and Violle, C. (2015), cati: an R package using functional traits to detect and quantify multi-level community assembly processes. Ecography. doi: 10.1111/ecog.01433"
