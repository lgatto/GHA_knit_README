# Knit my README.Rmd GitHub Action

This GitHub Action (GHA) knits the `README.Rmd` file to generate an
up-to-date `README.md` file. 


As an example, the following code chunk evaluates `1 + 1` and will
dispaly `[1] 2` in the `README.md` output file.


```r
1 + 1
```

```
## [1] 2
```

### Notes

- The newly knit `README.md` file will have to get pull locally every
  time.

### TODO

- If the repository hosts an R package and that the latest of that
  package is needed to properly knit the `README.Rmd` file, then an
  additional installation step is needed.

