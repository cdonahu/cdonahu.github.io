Update on How R Programming Is Going
================
Claudia Donahue
2022-06-27

## So Far This Summer…

We are just about halfway through the summer term (my final term in my
program!), and I have made plenty of progress. We are done learning
about how to program in R and the rest of the coursework will explore
other skills.

The coolest thing I have learned so far in the course is how to share my
work using R markdown and Github Pages. Before this course, I had a
brief introduction to programming in R about 4 years ago and had not
used it much since then. Markdown was not a big part of that weeklong
intro for me. I have found it really useful to create something I could
then pass along to a colleague who wants to know how I got my results or
how to replicate my work with their data.

Another thing I am happy to have learned in R is how to create custom
functions. This skill has been useful to develop so far my degree
program when I want to use an algorithmic method to solve certain types
of problems, but until now I have used other languages, like Python or
Julia.

Here’s an example of a custom function that, given a numeric vector and
a mean value to compare against, calculates the test statistic:

``` r
tStat <- function(vec, mean){
  
  tObs <- (mean(vec) - mean) / (sd(vec)/sqrt(length(vec)))
  
  return(tObs)
}
```

I look forward to learning more skills that will be useful in my career
in operations research!
