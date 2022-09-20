Data Import
================

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
    ## ✔ ggplot2 3.3.6      ✔ purrr   0.3.4 
    ## ✔ tibble  3.1.8      ✔ dplyr   1.0.10
    ## ✔ tidyr   1.2.0      ✔ stringr 1.4.1 
    ## ✔ readr   2.1.2      ✔ forcats 0.5.2 
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

# Data Import: CSVs

Let’s import data using the `readr` package. We want to use relative
paths (meaning starting from the R project) to indicate where existing
files are. We can also send this relative path to others with similar
folder names, and they will be able to use it as well.

``` r
litters_df = read.csv("data_import_examples/FAS_litters.csv")
```
