# Slides for IS 407

## Course Slide Decks

- [week1-01-welcome](week1-01-welcome).

- [week2-01-data-viz](week2-01-data-viz).

- [week2-02-viz-num-cat](week2-02-viz-num-cat).

- [week3-01-tidy+wrangle](week3-01-tidy+wrangle).

- [week4-01-df-join](week4-01-df-join).

- [week4-02-tidying](week4-02-tidying).

- [week5-01-data-type+class](week5-01-data-type+class).

- [week5-02-data-import+recode](week5-02-data-import+recode).

- [week6-01-web-scrape](week6-01-web-scrape).

- [week6-02-d19-top-250-imdb](week6-02-d19-top-250-imdb).

- [week7-01-functions+iteration](week7-01-functions+iteration).

- [week9-01-studies-confounding](week9-01-studies-confounding).

- [week9-02-effective-dataviz](week9-02-effective-dataviz).

- [week10-01-language-of-models](week10-01-language-of-models).

## Dev Toolkit Notes

Slides are built in using the **xaringan** package. See [here](https://github.com/yihui/xaringan) for more info on xaringan. There are two main reasons for choosing this format:

1. `xaringan` slides are R Markdown based, meaning code, output, and narrative can all live in one place and compiling the slides will run the R code as well.
2. Slide output is mobile friendly.

### Dev Instructions

Each slide deck is in its own folder, and one level above there is a custom css file. To compile the slides use `xaringan::inf_mr(cast_from = "..")`. This will launch the slides in the Viewer, and it will get updated as you edit and save your work.

## Acknowledgements

This course and materials are supported by and highly indebted to Mine Centinkaya-Rundel and Posit Education Team.
