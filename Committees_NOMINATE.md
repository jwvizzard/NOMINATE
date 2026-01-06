Armed Services Committees NOMINATE Visualization
================

## Armed Services Committee Rosters

# The membership for the House and Senate Armed Services Committees (including the House National Security Committee in the XXX and XXX Congresses) was derived from the committees’ reports of activities.

# Committees published these reports on varying schedules, sometimes long after the Congress to which they referred. The reports were unavailable for some Congresses, and I assembled membership information from other sources, including C-SPAN hearings, which often list the committee membership.

# These lists include ALL members of the committee during that Congress, including those who left the committee or joined late. There are a few exceptions, for instance in the 102nd Congress, I included Mary Bono but not Sonny Bono because he died at the beginning of the session and played no part in the hearings covered by this project.

# There are several issues with NOMINATE scores, but they are the most readily available and consistent measure of ideology.

# 1. NOMINATE scores are consistent for a single member across their membership in a legislative body, so they do not capture ideological evolution. Therefore, these measures may under- or overstate a member’s ideological extremism at any given point.

# 2. The NOMINATE dimensions do not directly address military and national security issues. It is possible that there are outliers who score extremely conservative on the economic or racial scale by are liberal on national security issues. However, that seems less likely during the period of this study–for instance Democrats like Joe Lieberman who were hawkish and conservative on national security were also among the most conservative members of their party on other issues.

## Code

``` r
library(tidyverse)
```

    ## Warning: package 'ggplot2' was built under R version 4.5.2

    ## Warning: package 'tidyr' was built under R version 4.5.2

    ## Warning: package 'readr' was built under R version 4.5.2

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.4     ✔ readr     2.1.6
    ## ✔ forcats   1.0.1     ✔ stringr   1.6.0
    ## ✔ ggplot2   4.0.1     ✔ tibble    3.3.0
    ## ✔ lubridate 1.9.4     ✔ tidyr     1.3.2
    ## ✔ purrr     1.2.0     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
library(usethis)
```

## Including Plots

You can also embed plots, for example:

![](Committees_NOMINATE_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
