---
layout: page
title: Research Projects
subtitle: 
---


#### (Apr 2020 - Present) Demographic, Social, and Physiological Vulnerabilities related to Development of COVID-19 Symptoms: A Prospective Digital Health Study

On July 17, 2020, the CDC updated their list of illnesses that are risk factors for COVID-19. Factors with “strongest and most consistent evidence” include hypertension, heart disease, cancer, and obesity, and demographic vulnerabilities are age, sex, minority race, and low SES. Social and psychological factors like stress, discrimination, and depression are less examined but may be critical factors in the disease contagion processes. In this project, we examine (i) psychophysiological vulnerability factors related to developing COVID-19 symptoms, (ii) mitigating factors associated with reduced symptomatic features, and (iii) the effect of randomly assigning people to stressreduction techniques aimed at reducing blood pressure or a control group.  <br/>


#### (Sep 2019 - Present) Diversity and Representation Constraints in Multiwinner Elections


Recent work in the study of fairness in multiwinner elections focuses on settings where candidates have attributes. However, voters may also be divided into predefined populations under one or more attributes (e.g., "California" and "Illinois" populations under the "state" attribute), which may be different from candidate attributes, and models that focus on candidate attributes alone may systematically under-represent smaller voter populations. Hence, we develop a model, DiRe Committee Winner Determination (DiReCWD), which delineates candidate and voter attributes and selects a committee (i) using diversity constraints to lower-bound the number of candidates selected from each candidate group, (ii) using representation constraints to lower-bound the number of candidates elected by each voter population, and (iii) maximizing the score of the committee subject to meeting the constraints.

DiReCWD has the flexibility to specify diversity and representation constraints, and a voting rule, thus incorporating diverse committee winner determination and the apportionment problems as example special cases. We analyze the computational complexity of selecting a committee under DiReCWD, and study the inapproximability and parameterized complexity. We present an empirical analysis of feasibility and of the utility traded-off to satisfy the constraints. <br/>
[in-submission]

#### (Jan 2019 - Present) Algorithmic Techniques for Necessary and Possible Winners

We investigate the practical aspects of computing the necessary and possible winners in elections over incomplete voter preferences. In the case of the necessary winners, we show how to implement and accelerate the polynomial-time algorithm of Xia and Conitzer. In the case of the possible winners, where the problem is NP-hard, we give a natural reduction to Integer Linear Programming (ILP) for all positional scoring rules and implement it in a leading commercial optimization solver. Further, we devise optimization techniques to minimize the number of ILP executions and, oftentimes, avoid them altogether. We conduct a thorough experimental study that includes the construction of a rich benchmark of election data based on both real and synthetic data. Our experimental findings suggest that, the worst-case intractability of the possible winners notwithstanding, the algorithmic techniques presented here scale well and can be used to compute the possible winners in realistic scenarios.  <br/>
[pre-print](https://arxiv.org/pdf/2005.06779)

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

