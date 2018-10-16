+++
# Project title.
title = "Consulting Project F17-05"

# Date this page was created.
date = 2018-05-22T00:00:00

# Project summary to display on homepage.
summary = "Effect of Avatar Characteristics on In Game Conversations"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Dota"]

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

**Dates (begin--end):** 10/27/2017 -- 5/22/2018

**Consultant(s):** Yuxin Zou (coL), Jason Willwerscheid (coL), Juan Mora, Daniel Xiang

**Client(s):** Ross Burkholder, PhD student, Linguistics

**Project Aim:**

The project investigates whether a Dota 2 player's avatar's characteristics affect the usage of emojis and polite words during a game.

**Project Description:**

Prior linguistics studies have examined the differences in the way that different people talk. In recent years, linguists have become interested in how these differences in face-to-face communication have been transposed onto the written medium, particularly with the rise of texting and the internet. Previous studies have shown that players controlling avatars clothed in black robes use more aggressive language than players controlling avatars in white robes. 

The data come from the chat log in Dota 2. Given the data set of 95524 cases (game id - avatar pair), each with 4 predictor variables (avatar's names, gender, role and whether the game is customized) and response variables (politeness/emoji counts, total messages), we were asked to perform inference on the effect of these predictors on counts of emojis and `polite' words used.

**Basic Methodology:**

Since the response variables are count data, and they are bounded by the total number of messages in the game, it is natural to use a generalized linear model with binomial distribution. However, since the counts of emojis and `polite' words are small, we fit a poisson linear model on the rate. The predictors are gender (3 level factors), role (2 level factors) and whether the game is customized. Because the players interact with each other in a game, we add game id as a random effect.

**Results:**

We found that custom games had a significant positive effect for emoji counts and a negative effect for politeness word counts. Gender had a significant effect only with respect to the politeness response. Players who chose female hero avatars used more polite words in the games than players using male/neutered heroes. Support roles had a significant negative effect only with respect to the emoji response.
