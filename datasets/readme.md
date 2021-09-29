
Datasets used in Fall 2021 for LING 172. 

## Class survey data

Data from the class survey can be downloaded at: [https://kathrynschuler.com/ling172/datasets/class-survey-data.csv](https://kathrynschuler.com/ling172/datasets/class-survey-data.csv) or loaded directly into r with:

```r
data <- read.csv('https://kathrynschuler.com/ling172/datasets/class-survey-data.csv')
```
## Wordbank data

Cross-linguistic trajectories of two words: `ball` and `dog` from [wordbank.stanford.edu](http://wordbank.stanford.edu/analyses?name=uni_lemmas). Download the dataset at: [https://kathrynschuler.com/ling172/datasets/crosslinguistic-dog-ball.csv](https://kathrynschuler.com/ling172/datasets/crosslinguistic-dog-ball.csv) or load directly into r with:

```r
data <- read.csv('https://kathrynschuler.com/ling172/datasets/crosslinguistic-dog-ball.csv')
```

## Language diversity data

A long format dataset that is most useful in wide format. Data taken from Appendix 1 in:
Nettle, D. (1998). Explaining Global Patterns of Language Diversity. Journal of Anthropological Archaeology, 17, 354–374.

[Nettle, D. (1998). Explaining Global Patterns of Language Diversity. Journal of Anthropological Archaeology, 17, 354–374.](https://kathrynschuler.com/ling172/datasets/nettle-1998.pdf)

To use this dataset, you'll need the jvcasillas/untidydata package:

```r
install.packages("devtools")
devtools::install_github("jvcasillas/untidydata")
```

Then call

```r
language_diversity
```

