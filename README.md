# Workshop <img src="img/hex-MrBean.png" width="120px" align="right"/>

<br/> <br/>

<img src="img/picture.jpg" width="100%" />

## Installation

You can install the MrBean package:

``` r
devtools::install_github("AparicioJohan/MrBeanApp")       
remotes::install_github("AparicioJohan/MrBeanApp")   
```
or you can go to https://mrpackages.netlify.app/mrbean.html and donwload it from there.

```r
file <- rstudioapi::selectFile()
remotes::install_local(  file )
```

## Example

``` r
library(MrBean)
run_app()
```
