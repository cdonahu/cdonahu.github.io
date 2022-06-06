Programming Background
================
Claudia Donahue
2022-06-06

## My Experience So Far

The majority of my programming experience was in the Fall 2021 term in
`ISE 535 Intro to Python`. I also did a weeklong course,
`Intro to R Programming` in 2018, and I took an introductory course in
`SAS` during the summer of 2021. Unfortunately, at work I usually use
Excel, and my programming gains atrophy quickly.

My thoughts on `R` so far in this course: I really like using Markdown
in `R` to create a readable document. I think that this tool/skill will
help me use `R` at work to create products for my coworkers who may not
know anything about `R` or have any interest. And also for those who do,
so they could understand and reproduce my work.

I also like using RStudio with Github so far, for version control. I
have had trouble working on projects with partners/groups because we are
all working on one file and can’t figure out how to best merge changes,
so one team member does most of the work.

I don’t think I will miss much about other programming languages,
especially Python since I am using it regularly in another course this
summer! I do not consider R any more or less difficult than the other
programming languages I have experienced, and it is much easier than
foreign languages I have tried to learn, specifically Russian and
French.

## R Markdown Output

Below, I am going to plot the Cars data set to make sure I can get the
image to show up on my blog post:

``` r
plot(cars, xlab = "Speed (mph)", ylab = "Stopping distance (ft)",
    las = 1, xlim = c(0, 25))
```

![](../images/Plot%20of%20Cars%20data-1.png)<!-- -->
