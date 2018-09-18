
## A Tiny R pkg

### Build:

`R CMD build sotenbori`

### Check:

```
R CMD check sotenbori_0.1.0.tar.gz --as-cran
```

### Install & View help

```
devtools::install_github("tcgriffith/sotenbori")
library(sotenbori)

help(sotenbori::hello)
```
