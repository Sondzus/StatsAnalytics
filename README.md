# StatsAnalytics
Some of the notes for course materials on Applied Computational Statistics for Analytics, ITMD/ITMS/STAT 514 offered at Illinois Tech.

## Overview
The course materials were developed during Fall 2020 and Spring 2021. Future updates will be posted as the course evolves. 

## Course info
[Here](https://www.sonjapetrovicstats.com/teaching/514sp21) is the course homepage for the recent semester, Spring 2021, which contains the course syllabus, topics, and more information. 

## Types of files

* html - course handouts. 
 
 <!-- 
 IF YOU ARE VIEWING IN RAW GITHUB: 
 **Note** To preview within the browser, prepend `https://htmlpreview.github.io/?` to the path in your browser, such as [here](https://htmlpreview.github.io/?https://github.com/Sondzus/StatsAnalytics/blob/master/514-1.1-handout-DescriptiveStatistics.html) 
 --> 
 
* PDF - slides for short illustrations used within a live lecture
* Rmd - raw R Markdown code. This is provided when students need to see the code. Additional code is always provided with weekly homework assignments and labs, not for each lecture.   


### Schedule 

#### Week 1 - Reasoning with data / framework for viewing data 

* [lecture slides PDF](https://github.com/Sondzus/StatsAnalytics/blob/master/514-slides-day1-welcome.pdf)
    * Additional notes on reasoning with data are written live. 
* Interlude: create your first .Rmd file!   All of your HW will be submitted using markdown and html/pdf. Here are some templates, just so you know what to expect:
    * [514-hw-template.Rmd](514-hw-template.Rmd)
    * [514-hw-template.html](514-hw-template.html)
    * [514-hw-template.pdf](514-hw-template.pdf)

* How to use Python within RStudio via the Reticulate package: [view video](https://drive.google.com/file/d/1_pbx5jKmjlEslbSk2XQ6hOVzwn6_ePHM/view?usp=sharing) 

#### Week 2  - Types of random variables, measures of location and scale, basic summary statistics 

- Notes: 

		* [514-1.1-handout-DescriptiveStatistics](514-1.1-handout-DescriptiveStatistics.html); [view plain html version](514-1.1-handout-DescriptiveStatistics-plainMarkdown.html) and the [source file .Rmd](514-1.1-handout-DescriptiveStatistics-plainMarkdown.Rmd)
		
- Interlude: Overview of R&Python, packages, scripts, loading, basics, importing an example data set (part I)

    * [514-0.1-handout-AboutRandPython](514-0.1-handout-AboutRandPython.html)
    * [514-0.2-handout-RMarkdown](514-0.2-handout-RMarkdown.html) 



#### Week 3 - Sampling distributions 

* in-class worksheet on [Sampling distributions](514-1.2-handout-SamplingDistributions.html)

- Interlude: Overview of Markdown and basic R functionality (part II, continuation of handouts from week 2)





#### Week 4 - The link between sampling distributions, inference, analytics, EDA 

* Overview of analytics vs. EDA vs. inference (handwritten notes) 

<!-- for Yuhan: [notes](https://drive.google.com/file/d/1HPrBbAhFzFR5jXG898Yu9fg7P58CWtKT/view?usp=sharing) --> 

* In-class lab worksheets for Bar graphs, Histograms, and binning provided in class forum through links. 

> Work through bar graphs and histograms worksheets in both R and Python. Once you see the word ‘binning’, you can come back to this step and also walk through the binning worksheet. These are linked from one of our reference texts. 


<!-- for Yuhan: can be found in the links on the HW3 file in #48 on campuswire. --> 

- Interlude: functions in R
    * [slides](514-1.interlude-slides-R.functions.pdf)
    * [handout](514-1.interlude-handout-R.functions.html)


#### Week 5 - Sampling distributions: location parameters 

* Here are slides I plan to use in the lecture on 2/22: 

    * [514-2.1-slides-SamplingdistributionMean.pdf](514-2.2-slides-SamplingdistributionMean.pdf)
    * [514-2.2-slides-SamplingdistributionDifferenceInMeans.pdf](514-2.2-slides-SamplingdistributionDifferenceInMeans.pdf)
    
* Here are "R interlude" notes on how to do some basic data cleanup operations in R: 

    * [514-1.interlude-handout-R.DataCleaning.Iterations.html](514-1.interlude-handout-R.DataCleaning.Iterations.html)


#### Week 6 - Sampling distributions - location and scale parameters 

* [514-2.3-slides-SamplingDistributionMeanS-tDistribution.pdf](514-2.3-slides-SamplingDistributionMeanS-tDistribution.pdf)
* [514-2.4-slides-BasicsOfInference-S2-FDistribution.pdf](514-2.4-slides-BasicsOfInference-S2-FDistribution.pdf)



#### Week 7 - Quantile plots & overview of EDA

* [514-2.5-slides-BasicsOfInference-QuantilePlots](514-2.5-slides-BasicsOfInference-QuantilePlots.pdf)
* Adult census data set [adult.csv](https://campuspro-uploads.s3.us-west-2.amazonaws.com/961e3137-b34e-4ebe-923b-11b0195d78ce/b9a55571-2ed2-48ab-9f9d-2d93f748ca27/adult.csv)
* About exploratory data analysis, or EDA [514-2.6-slides-EDA.pdf](514-2.6-slides-EDA.pdf)

> Note: additional notes on quantiles definitions are included in the first 25 minutes of the lecture video. 


#### Week 8 - Confidence intervals 

* [confidence intervals slides](514-2.7-slides-BasicsOfInference-ConfidenceIntervals.pdf)
* [location problem examples slides](514-2.7-slides-BasicsOfInference-ConfidenceIntervals.LocationProblemExamples.pdf)

* [514-2.7-handout-BasicsOfInference-ConfidenceIntervals](514-2.7-handout-BasicsOfInference-ConfidenceIntervals.html)
* [514-2.7-handout-BasicsOfInference-ConfidenceIntervals.LocationProblemExamples](514-2.7-handout-BasicsOfInference-ConfidenceIntervals.LocationProblemExamples.html)

* **code**:  here is all the  R code needed to run the lecture examples on your computer: 
    * [code for week 8 part 1](wk8code-1.Rmd)
    * [code for week 8 part 2](wk8code-2.Rmd)


* R tools for EDA handout: [514-2.6-handout-RtoolsForEDA.html](https://htmlpreview.github.io/?https://github.com/Sondzus/StatsAnalytics/blob/master/514-2.6-handout-RtoolsForEDA.html)



#### Week 9 - overflow & midterm

Midterm exam  & oral exam meetings & lecture time overflow. 


#### Week 10 - Hypothesis testing and p-values

* [514-2.8-slides-BasicsOfInference-HypothesisTests.pdf](514-2.8-slides-BasicsOfInference-HypothesisTests.pdf)
     * what you **must** know (at the level of being able to explain it to someone): [quick summary - critical info - PDF](https://drive.google.com/file/d/1F77lkjIn7gtrYi3lq8pscqV9wI0dgNTu/view?usp=sharing)
   * **breakout room example** : [514-extra-example%20and%20p%20value%20on%20testing.pdf](https://campuspro-uploads.s3.us-west-2.amazonaws.com/961e3137-b34e-4ebe-923b-11b0195d78ce/960501d7-3337-4f32-a3a7-7085716465fa/514-extra-example%20and%20p%20value%20on%20testing.pdf)

* [extra on p-values and testing](514-2.8-extra-example and p value on testing.pdf)


#### Week 11 - Introduction to statistical learning  and learning&estimation tradeoff

* [514-3.1-WhatIs-StatisticalLearning.pdf](514-3.1-WhatIs-StatisticalLearning.pdf)
* [514-3.2-StatisticalLearning-EstimationTradeoff.pdf](514-3.2-StatisticalLearning-EstimationTradeoff.pdf)



#### Week 12 - Model accuracy and intro to regression 

* [model accuracy](514-3.3-StatisticalLearning-ModelAccuracyEtc.pdf) -- a high-level overview of what it is 
* [regression - intro](514-4.1-Regression-Intro.pdf)
* Some of you have asked about the code I used for regression in R. [Here is a handout](514-4.2-handout-Regression-HandsOn.html) for you to walk through, which is at the same time this week's homework. :) 



#### Week 13  - Regression: diagnostics and extnesions 

* [Regression - Model Diagnostics](514-4.2-slides-Regression-ModelDiagnostics.pdf)
* [Regression - extensions](514-4.3-slides-Regression-Extensions.pdf) (the `why` and `who cares` of regression; prediction intervals)
* Interlude: 
    * [Python - pandas basics](514-handout-Python-Pandas-Basics.html) **a handout** that may come in handy! 

> Study tip (if you have notes from spring 2021): compare page 5 of notes from week 12 regression to lats page of notes from week 13. We ask/then answer the 7 questions about designing a marketing plan!  


#### Week 14 - Regression - the whole story w/ example 

* [Regression - start to finish](514-4.4-handout-RegressionWihtExamples.html)  -- this is the handout on which the lecture is based. 
* Hands-on lab markdown file  posted during the lecture: [514-4.4-lab-Regression1.Rmd](514-4.4-lab-Regression1.Rmd) and [514-4.4-lab-Regression1.html](514-4.4-lab-Regression1.html) 

.
.
.
* you've solved it? Check your solution against [this](514-4.4-lab-Regression1-Solution.Rmd). 



#### Week 15 - Crossvalidation and why 

* [514-4.5-slides-Regression-WhyWeCrossValidate-Wrapup.pdf](514-4.5-slides-Regression-WhyWeCrossValidate-Wrapup.pdf)
* [Cross-validation LAB](514-4.5-lab-ValidationCrossvalidationR-WithSolutions.html) - in this document, solutions are already included. Watch the last part of the lecture to figure out what to do. 
    * [LAB Rmd file](514-4.5-lab-ValidationCrossvalidationR-WithSolutions-shared.Rmd)



<!-- 

During Sp2021, one of the ice breaker questions was to describe your dream team. Here is what you said: 

![ITMdreamteam.png](https://campuspro-uploads.s3.us-west-2.amazonaws.com/961e3137-b34e-4ebe-923b-11b0195d78ce/359073f4-03e3-4f70-8a2d-83e5c6633198/ITMdreamteam.png)

--> 

## License
This folder and all the documents. within it  is created by Sonja Petrovic for ITMD/ITMS/STAT 514, Spring 2021, at Illinois Tech. 

While the course materials are generally not to be distributed outside the course without permission of the instructor, all materials posted on this page are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).


[![Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][image]][hyperlink]

  [hyperlink]: https://creativecommons.org/licenses/by-nc-sa/4.0/
  [image]: https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png
    
