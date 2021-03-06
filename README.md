
<!-- README.md is generated from README.Rmd -->

## visProteomics

**visProteomics** helps with the exploration and visualization of
proteomics data obtained with the process of fractionation.
Fractionation of samples is often used in proteomics to improve
signal-to-noise ratio and proteome coverage. **visProteomics** explores
attributes of proteins detected in different fractions through both
graphical and tabular representation.

Venn/Euler diagrams are widely used for data summarization and there are
many plotting tools available. **visProteomics** defines a complementary
tabular function. The resulting data frame summarizes attributes of
elements found in different regions of the Venn diagram. This generic
function can be used for any data set.

## visProteomics package as part of proteomics analysis

![visProteomics_illustration](https://user-images.githubusercontent.com/37818185/124632049-459e8c80-de84-11eb-814e-9f80fdb10245.png)

## Installation

``` r
devtools::install_github("ivabudimir/visProteomics")
```

For installation of vignettes together with the package, add
“build\_vignettes=TRUE”.

## Usage

Please check
[visProteomics](https://ivabudimir.github.io/visProteomics/) website.

Alternatively, read vignettes *merge-fractions* and *vis-fractions* for
the exploration and visualization of a fractionated proteomics sample.
For the tabular Venn function, read *explore-venn* vignette.

## License

visProteomics is open source software, licensed under
[GPL-3](https://github.com/ivabudimir/visProteomics/blob/master/LICENSE).
