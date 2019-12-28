+++
title = "Code"
weight = 20
draft = false
+++

{{< figure class="image main" src="/images/pic02.jpg" >}}
### Lung Cancer Risk Factor R Package
A person's smoking history can inform them about their risk of lung cancer, but what about those of us who have never smoked? can't we get lung cancer too, and how do you figure out our risk? Along w Summer Han,  I developed an R package that simulates other lung cancer risk factors using the smoking history generator developed by CISNET.  [Check it out on my github.](https://github.com/ekhco/LCsim)

###  Bias and Efficiency in Matched Study Designs
I developed and tested an algorithm in R that matches cases and controls with varying cluster ratios (instead of a fixed 1:n ratio), for studies where it is difficult to recruit sufficient controls.  I presented this work at the Joint Statistical Meeting in Colorado (JSM 2019).

### Spontaneous Coronary Artery Dissection
I was the statistical lead on a multi-center study of SCAD. I advised the primary investigators on study design, appropriate statistical methods, and data collection. I have a junior statistician who helps me with this, which is nice.

### Predicting HIV in the Demographic Health Surveys
I used conditional inference trees to see if there were any novel factors that may be predictive of HIV status of individuals in sub-Saharan Africa, using sort-of big data from the Demographic Health Surveys.

### Liver Simulated Allocation Model
Allocation of donated organs to people with liver disease is challenging in the US. I worked with [mathematicians](https://www.usna.edu/Users/math/gentry/index.php), data from the [Scientific Registry for Transplant Recipients](http://www.srtr.org), and used simulation models to study hypothetical allocation systems that give people with liver disease a fairer chance at a life-saving liver transplant, regardless of where they live.

### Kidney Paired Donation
The [National Kidney Registry](http://www.kidneyregistry.org) arranges domino kidney transplants in the US.  We studied the associations between transporting kidneys (and the time they are put on ice) and how well the kidneys and patients do. This required plenty of data cleaning, linking, and survival/logistic regression in Stata.

### Detecting Pneumonia with Machine Learning
Can a stethoscope and a smartphone be used to listen to your breathing and warn you about potentially abnormal conditions? [Clinicloud.com](http://clinicloud.com) has the answer to this problem. I worked with them to develop neural-net algorithms for heart-rate and pneumonia detection in R.

### Patient-Centered Decision Modelling
I wrote Markov models in C (and PhP) to help inform patient-centered decision problems.  In one decision problem, kids with kidney disease have to decide whether they should accept a kidney from a willing donor that they know, or if they should wait to get one from the deceased donor waitlist and "save" the other one for later. [Check out the online decision-tools I have made here.](http://www.transplantmodels.com)

Check out [my peer-reviewed papers](#about)