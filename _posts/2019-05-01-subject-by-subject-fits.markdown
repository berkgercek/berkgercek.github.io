---
layout: post
title:  "Examples of single-subject fits of the ideal-observer model for visual search."
date:   2019-05-01 20:16:20 +0200
categories: visual search
---
The code for generating these fits can be found at [my github](https://github.com/berkgercek/) as well as all code describing the model! All interactive plots were generated via the [plotly](https://plot.ly/python/) library for python.

# Interactive fits

Our model proves to be robust in describing many different regimes of subject reaction times, ranging from distributions of RT with a separation of 1-2 seconds:  
[No reward, set size of 12 stimuli (35 trials per condition)](/assets/subject_1_exp1_single_N_12_modelfit.html)  
[No reward, set size of 16 stimuli](/assets/subject_4_exp1_single_N_16_modelfit.html)

To those in which the reaction times for target-present and target-absent trials are nearly overlapping:  
[Reward given for correct absent responses, set of 8 stimuli](/assets/subject_5_exp2abs_single_N_8_modelfit.html)

To those in which subject reaction time distributions are spread out over the course of the entire allowable time for the trial:  
[Reward given for correct absent responses, set of 12 stimuli](/assets/subject_6_exp2abs_single_N_16_modelfit.html)

**It should be noted that while there is some jaggedness on the curves describing the simulated reaction time distributions, these are computational artefacts that arise from backwards induction. They can be removed provided enough time is given for the simulation to run, but were not for these fits for the sake of expedience.**

<!-- Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->
