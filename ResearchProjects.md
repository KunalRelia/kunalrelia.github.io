---
layout: page
title: Research Projects
subtitle: 
---
#### (Sep 2019 - Present) The *"Five Ws"* of Fairness in Multiwinner Elections

Fairness has recently received particular attention from the computer science research community. However, context-specific uses of a complex term like "fairness" narrate an incomplete story, possibly doing more harm than good. For example, an unintended consequence of fair elections with respect to candidates can be unfairness to voters, and vice versa.

Hence, we propose to move towards completing the story of fairness by answering the *Five Ws*, namely, the *Who, What, When, Where, Why,* and *How*, which have been used in fields like scientific research, politics, and journalism to ensure thoroughness of the work done. We use the context of multiwinner elections, also known as committee selection, and advance to formally answer each question by designing algorithmic frameworks and giving axiomatic guarantees wherever possible. Our initial results show that finding a committee under our framework is generally computationally hard, and, for such cases, we study the inapproximability and parameterized complexity of the problems. As part of our work, we show that efficient algorithms exist under some real-world assumptions, such as when preferences follow a particular kind of structure. In addition to theoretical results, we conduct extensive empirical analysis. Overall, through a series of investigations and using multiwinner elections as an example, we show that any "fair" system with an incomplete story can have adverse outcomes, and with an advent of automated decision systems in all fields, even a context-specific "fair" system can unknowingly impact millions of people negatively. Immediate action is required to ensure that algorithm designers understand the responsibility associated with the claim of "fairness".  The goal of this work is to move towards a more complete story in this important domain. <br/>
[pre-print 1](https://arxiv.org/pdf/2107.07356.pdf)

#### (Apr 2020 - Present) Demographic, Social, and Physiological Vulnerabilities related to Development of COVID-19 Symptoms: A Prospective Digital Health Study

On July 17, 2020, the CDC updated their list of illnesses that are risk factors for COVID-19. Factors with “strongest and most consistent evidence” include hypertension, heart disease, cancer, and obesity, and demographic vulnerabilities are age, sex, minority race, and low SES. Social and psychological factors like stress, discrimination, and depression are less examined but may be critical factors in the disease contagion processes. In this project, we examine (i) psychophysiological vulnerability factors related to developing COVID-19 symptoms, (ii) mitigating factors associated with reduced symptomatic features, and (iii) the effect of randomly assigning people to stressreduction techniques aimed at reducing blood pressure or a control group.  <br/>

#### (Jan 2019 - Present) Algorithmic Techniques for Necessary and Possible Winners

We investigate the practical aspects of computing the necessary and possible winners in elections over incomplete voter preferences. In the case of the necessary winners, we show how to implement and accelerate the polynomial-time algorithm of Xia and Conitzer. In the case of the possible winners, where the problem is NP-hard, we give a natural reduction to Integer Linear Programming (ILP) for all positional scoring rules and implement it in a leading commercial optimization solver. Further, we devise optimization techniques to minimize the number of ILP executions and, oftentimes, avoid them altogether. We conduct a thorough experimental study that includes the construction of a rich benchmark of election data based on both real and synthetic data. Our experimental findings suggest that, the worst-case intractability of the possible winners notwithstanding, the algorithmic techniques presented here scale well and can be used to compute the possible winners in realistic scenarios.  <br/>
[ACM/IMS TDS'21](https://dl.acm.org/doi/10.1145/3458472) <br/>


#### (May 2018 - Jan 2019) Discrimination in Social Media and Hate Crimes Across 100 U.S. Cities

We study malicious online content via a specific type of hate speech: race, ethnicity and national-origin based discrimination in social media, alongside hate crimes motivated by those characteristics, in 100 cities across the United States. We develop a spatially-diverse training dataset and classification pipeline to delineate targeted and self-narration of discrimination on social media, accounting for language across geographies. Controlling for census parameters, we find that the proportion of discrimination that is targeted is associated with the number of hate crimes. Finally, we explore the linguistic features of discrimination Tweets in relation to hate crimes by city, features used by users who Tweet different amounts of discrimination, and features of discrimination compared to non-discrimination Tweets. Findings from this spatial study can inform future studies of how discrimination in physical and virtual worlds vary by place, or how physical and virtual world discrimination may synergize. <br/>
[AAAI ICWSM'19](https://wvvw.aaai.org/ojs/index.php/ICWSM/article/download/3354/3222/)<br/>

#### (Sep 2016 - Nov 2018) Socio-Spatial Self-Organizing Map

Historically, neighborhoods have been defined using administrative boundaries like Zip codes. But, it is a growing understanding in social sciences that what we experience around us is different from what is captured by such administrative boundaries. Hence, we develop a novel pipeline, Socio-Spatial Self-Organizing Map (SS-SOM), that uses freely-available, sparse, geo-tagged social media data to assess relevant geographies to measure exposure to social processes. The pipeline uses (i) shallow neural network to classify Tweets, (ii) followed by dividing the city into grid-cells, and (iii) then using an augmented version of the Self-organizing Maps to create contiguous, non-overlapping, homogeneous clusters. We use prevalence of racism and homophobia in New York City as example social processes to measure the change in exposure to these social processes between Zip codes and SS-SOM clusters.<br/>
[ACM CSCW'18](https://dl.acm.org/citation.cfm?id=3274414)

#### (Sep 2016 - Oct 2018) Filling User Timeline Using Sparse Social Media Data

A stochastic framework for predicting individual level mobility timelines using sparse location data from social media. The framework utilizes individual and community mobility patterns and prioritizes the effect of location data closer in time, to make predictions. <br/>
[ACM SIGSPATIAL'18](https://dl.acm.org/citation.cfm?id=3274982)

#### (Jun 2016 - Dec 2016) Predicting Age and Gender of Social Media Users

Demographic attributes like age and gender are considered important covariates in public health study. Moreover, while data from social media platforms like Twitter is increasingly used in public health research, companies' policy of not sharing  users' demographic attributes act as a bottleneck in such analysis. Hence, we use the text of the Tweets made by users to infer their age using modern NLP techniques, and use user-names to infer the gender of the users. <br/>
[AAAI ICWSM'18](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/viewPDFInterstitial/17846/17048), [ACM CSCW'17](https://dl.acm.org/ft_gateway.cfm?id=3134689&type=pdf)

