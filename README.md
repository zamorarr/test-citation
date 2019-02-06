Custom Citations
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

The purpose of this README is to demonstrate using a custom *csl* file
and *yaml* bibliography to change the formatting of citations in
RMarkdown documents.

## Citation Style Language

The file *my-cool-style.csl* contains a simple custom citation style
that was generated using a [visual
editor](http://editor.citationstyles.org/visualEditor).

The custom style specifies that:

  - the citation should contain only the citation-number in superscript.
  - the bibligraphy entries are prefixed by a left bracket, suffixed by
    a right bracket, delimted by a forward slash.

## YAML Bibliography

Instead of using a common bibTex file to record bibliographic entries,
this project uses a YAML file. The *biblio.yaml* file is machine and
human readable and allows for custom field entries that are not
typically allowed by bibTex.

## Example Usage

This is an R Markdown
document<sup>[<span class="csl-baseline">1</span>](#ref-item1)</sup>.
Markdown is a simple formatting syntax for authoring HTML, PDF, and MS
Word
documents<sup>[<span class="csl-baseline">2</span>](#ref-WatsonCrick1953)</sup>.
For more
details<sup>[<span class="csl-baseline">3</span>](#ref-fenner2012a)</sup>
on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

## References

<div id="refs" class="references">

<div id="ref-item1">

1 \[John Doe / First book / 2005\]

</div>

<div id="ref-WatsonCrick1953">

2 \[J. D. Watson, F. H. C. Crick / Molecular structure of nucleic acids:
a structure for deoxyribose nucleic acid / April 1953 /
[10.1038/171737a0](https://doi.org/10.1038/171737a0) / 737–738\]

</div>

<div id="ref-fenner2012a">

3 \[Martin Fenner / One-click science marketing / March 2012 /
[10.1038/nmat3283](https://doi.org/10.1038/nmat3283) / 261–263\]

</div>

</div>
