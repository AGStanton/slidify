---
title       : Course Project Presentation
subtitle    : Developing an Intuition for the Size of Landmasses
author      : Albert Stanton
job         : Data Science Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The Vastness of the Earth

Have you ever tried to grasp the scale of our planet?

It can be difficult because most day-to-day activities relevant to our lives are on MUCH smaller scales.

Let's forget about the mind-blowing vastness of the universe for now, and just consider Earth.

Earth actually has a surface area of 196,936,994 square miles, or...


```r
## converting from square miles to square feet
## 5280 feet in one mile
print(196936994 * (5280^2)) 
```

```
## [1] 5.490288e+15
```

5.4902883 x 10^15 square feet. Wow, that's big. Maybe too big to really understand.

---

## How to Develop an Intuition

But wait, you don't have to resign yourself to a life of having a poor internal representation of large geographical entities.

In fact, a good starting point for "getting a feel" for large scales would be looking at landmasses.

If only there was a tool that allowed users to: 

1. Select a landmass
2. Select a familiar, tangible, widely known unit of measurement.
3. Express the size of that landmass in those familiar units.

I may have a solution...

---

## Introducing a Shiny App for Developing this Intuition

With my shiny app, you can 

1. Select any landmass with surface area greater than 10,000 square miles,
2. Select one of three familiar units of measurement (human, house, stadium), and
3. Have that landmass surface area expressed in those familiar units.

And boom, you have converted a mind-numbing number into something much more illustrative.

But who would want this, you might ask?

---

## Who is this App for?

This app is for:

1. Teachers trying to engage their students' imaginations.
2. Curious individuals wanting to sharpen their intuition.
3. People with an interest in geography.

Though this is a simple app, I hope you have enjoyed this presentation. Thanks for your time and consideration.

You can find the shiny app here:  https://agstanton.shinyapps.io/dataProducts/
