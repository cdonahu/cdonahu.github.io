Automating R Markdown
================
Claudia Donahue
2022-07-08

## The Assignment

Our second project in this summer course was to use [this
data](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) to
make several models to predict the number of times readers shared an
article from Mashable. The data set was split into six
channels–lifestyle, entertainment, business, social media, tech, and
world–and our job was to automate a report for each channel from a
single R Markdown file. We were also practicing building, testing, and
comparing regression and ensemble models, using the `caret` package in
R.

## Our Solution

You can see how our resulting six reports at [this
link](https://cdonahu.github.io/st558-project2/), and delve deeper into
how we solved the problem at our Github repo
[here](https://github.com/cdonahu/st558-project2).

## My Thoughts

Happily, I do not think I would do a lot differently. I am glad to say
we started working on this project as early as we could, and we had
plenty of time to complete the work. I did notice that our predictive
models were not making great predictions, so I might change the goal
from predicting the dependent variable (number of shares) to predicting
the *logarithm* of the number of shares.

The most difficult part I encountered was in building the random forest
model. I initially made the model so complex–both the tuning parameters
and the repeated cross-validation–that the `caret::train()` function
would run and run, never finishing. Once I simplified the model by
reducing the *mtry* tuning parameter and no longer repeating the
cross-validation, the model worked.

## The Takeaway

R Markdown is useful for so many reasons, and automating reports was
within my reach. I think understanding this concept could be useful for
me in the future.

Thanks for reading!
