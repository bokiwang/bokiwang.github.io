---
title: 'Beautiful Trajectories -- NMA 2020 Project'
excerpt_separator: "<!--more-->"
classes: wide
author_profile: true
---

<!-- In project category-->
Wait for Sami to finish clean up. Then generate the figures and gifs again

This is a cool computational neuroscience group project from NeuroMatch Academy 2020. 

The full project can be checked out at this repo, along with our video presentation. 

I'm interested in visualizing the timing information on the trajectory plot. If we can use an artifical decoder to decifer what the animal sees, and when the animal decided to move, then we can plot it out on the neural trajectory and see the timing info.

What is neural trajectory then?

Simply put, neural trajectories are a lower dimension representation of collective neural activities. Here is a really nice review article on it: [link](). We can use PCA to do dimensionality redunciton, and plot out two PCs against each other.     

How does the decoder work?
- GLM for decoder. 

Our dataset:
From the Steinmetz paper [link](). Mouse sees images of different contrasts, and will turn a wheel to indicate which side of the image is of high contrast. 

Methodological difficulty:
Run into an issue: not every subject has the same regions, and we rarely find someone with both primary visual and motor cortex.

Time for visualizations:
1. V1 4 contrasts
2. M1 2 contrasts.
Here's what a neural trajectory looks like, and we can see that it differentiates different visual stimuli (from V1) & motor choices (go-nogo from M1 and M2). 

3. A gif about timing information.
To put it all together, Here's a gif about how the decoder performs, about where timing happens with respect to visual trajectory and with respect to motor trajectory. re

So what?
We have to visualize complex information to gain insights that we cannot gain with simple information. It is helpful in developing an intuition in understanding the brain. 