
# test

# Assigning Values

``` r
dur_hablo_stressed <- 0.3872                #for the duration of "habló"
dur_hablo_unstressed <-  0.1584                 #for the duration of "hablo"

dur_o_stressed <- 6.9782                     #for the duration of the stressed [o]
dur_o_unstressed <- 5.4503                   #for the duration of the unstressed [o]

int_o_stressed  <- 65.7636    #for the intensity at the midpoint of the stressed [o]
int_o_unstressed <- 72.3922  #for the intensity at the midpoint of the unstressed [o]

f0_o_stressed <- 217.8978              #for f0 at the midpoint of the stressed [o]
f0_o_unstressed <- 245.1454          #for f0 at the midpoint of the unstressed [o]
```

# Calulating the Difference

``` r
dur_hablo_stressed - dur_hablo_unstressed
```

    ## [1] 0.2288

``` r
dur_o_stressed - dur_o_unstressed
```

    ## [1] 1.5279

``` r
int_o_stressed - int_o_unstressed
```

    ## [1] -6.6286

``` r
f0_o_stressed - f0_o_unstressed
```

    ## [1] -27.2476

# Observations

There were several things that I noticed when the calculations were
executed. I noticed that the duration in my stressed “habló” was longer
(0.3872) than in my unstressed “hablo.” The difference (0.2288) is
small, which I imagine when articulated can be difficult to perceive.
