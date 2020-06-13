
[![Build
Status](https://travis-ci.org/alastairrushworth/tdf.svg?branch=master)](https://travis-ci.org/alastairrushworth/tdf)
[![codecov](https://codecov.io/gh/alastairrushworth/tdf/branch/master/graph/badge.svg)](https://codecov.io/gh/alastairrushworth/tdf)

# `tdf`

## Installation

To install the package, use

``` r
devtools::install_github("alastairrushworth/tdf")
```

## Usage

Load the package and check out the help file

``` r
library(tdf)
?editions
```

Quick summary of the columns and their contents

``` r
tibble::glimpse(editions)

Observations: 106
Variables: 20
$ edition       <int> 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20,…
$ start_date    <date> 1903-07-01, 1904-07-02, 1905-07-09, 1906-07-04, 1907-07-08, 1908-07-1…
$ winner_name   <chr> "Maurice Garin", "Henri Cornet", "Louis Trousselier", "René Pottier", …
$ winner_team   <chr> "La Française", "Conte", "Peugeot–Wolber", "Peugeot–Wolber", "Peugeot–…
$ distance      <dbl> 2428, 2428, 2994, 4637, 4488, 4497, 4498, 4734, 5343, 5289, 5287, 5380…
$ time_overall  <dbl> 94.55389, 96.09861, NA, NA, NA, NA, NA, NA, NA, NA, 197.90000, 200.480…
$ time_margin   <dbl> 2.98916667, 2.27055556, NA, NA, NA, NA, NA, NA, NA, NA, 0.13555556, 0.…
$ stage_wins    <dbl> 3, 1, 5, 5, 2, 5, 6, 4, 2, 3, 1, 1, 1, 4, 2, 0, 3, 4, 4, 2, 3, 5, 1, 2…
$ stages_led    <dbl> 6, 3, 10, 12, 5, 13, 13, 3, 13, 13, 8, 15, 2, 14, 14, 3, 6, 15, 13, 8,…
$ height        <dbl> 1.62, NA, NA, NA, NA, NA, 1.78, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA…
$ weight        <dbl> 60, NA, NA, NA, NA, NA, 88, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA…
$ age           <int> 32, 19, 24, 27, 24, 25, 22, 22, 26, 23, 23, 24, 33, 30, 33, 36, 34, 29…
$ born          <date> 1871-03-03, 1884-08-04, 1881-06-29, 1879-06-05, 1882-10-18, 1882-10-1…
$ died          <date> 1957-02-19, 1941-03-18, 1939-04-24, 1907-01-25, 1917-12-20, 1917-12-2…
$ full_name     <chr> NA, NA, NA, NA, "Lucien Georges Mazan", "Lucien Georges Mazan", NA, NA…
$ nickname      <chr> "The Little Chimney-sweep", "Le rigolo (The joker)", "Levaloy / Trou-t…
$ birth_town    <chr> "Arvier", "Desvres", "Paris", "Moret-sur-Loing", "Plessé", "Plessé", "…
$ birth_country <chr> "Italy", "France", "France", "France", "France", "France", "France", "…
$ nationality   <chr> " France", " France", " France", " France", " France", " France", " Lu…
$ stage_results <named list> [[<data.frame[37 x 8]>, <data.frame[35 x 8]>, <data.frame[27 x …
```

## Comments? Suggestions? Issues?

Any feedback is welcome\! Feel free to write a github issue or send me a
message on [twitter](https://twitter.com/rushworth_a).
