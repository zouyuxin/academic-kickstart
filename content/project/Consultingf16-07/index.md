+++
# Project title.
title = "Consulting Project F16-07"

# Date this page was created.
date = 2017-02-07T00:00:00

# Project summary to display on homepage.
summary = "Neural effects of parental input on children"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Neural"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

**Dates (begin--end):** 10/25/2016 - 2/7/2017

**Consultant(s):** Tae Kim, Bumeng Zhuo, Siao Lu, Jiyi Liu, Sen Na, Yuxin Zou

**Client(s):** Ozlem Ece Demir-Lira

**Project Aim:**

This project investigates which aspects of mother's language use - quality or quantity or both - affect the child's cortical thickness in 5 different areas of the brain related to language.

**Project Description:**

The mother's language use, both quality and quantity, with her child at early home environment was measured three times when the child was 14, 30, and 42 months old. Then the child's cortical thickness in 5 language related areas were measured twice at around age 10 and around 14. Confounding variables of mother's IQ, income, education, and the children's gender and age at the measurement were provided.

The main issues include the correlation among the brain sites, correlation among the quality variable and quantity variable, and missing data (not all the children were measured twice). Two different scanners were used for brain imaging, so quality control must be also accounted for. Also, the interpretation of three different quality/quantity measure is unclear.

**Basic Methodology:**

We fit linear model on the three quantity/quality measures. The slope measures how the mother adjusts her language use to the child's cognitive development, and the intercept measures the average level of quality and quantity.

Then we used standard linear mixed effects model to see the effect of the explanatory variables. We used three variance components for the correlation among brain sites, correlation among the measurements from the same scanner, and an individual error term.

**Results:**

We found that the slope of the mother's language quality and its interaction with mother's IQ and mother's income have significant effect on the children's brains' cortical thickness. If this result can be reproduced with larger sample size, it could send an important message that mother's attention to a child's cognitive growth (slope of language quality) has higher impact when the mother earns less or has lower IQ. We suspect mothers with higher IQ and income tend to provide more outside resources to learn language like books or videos, so that the mother's language use has less effect on the children's language development. 

