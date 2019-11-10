---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Predicting Sepsis at Triage
_Fields Undergraduate Summer Research Program_ \
Xing Liu; supervised by Dr. Anna Goldenberg and Erik Drysdale \
_Abstract_: Sepsis is a lethal disease that causes millions of neonatal deaths annually, and one hour in the treatment procedure can make a huge difference for septic patients. In this regard, using machine learning approaches to help clinicans to make early Sepsis predictions has gain in popularity in recent years. Although many have shown promising predictive performance, these methods generally suffer from high false positive rates. We propose two neural network models that makes use of two natural language processing techniques, namely the TF-IDF and the Clinical BERT, and show experimentally how they could improve the predictive performance at medical triage. We train these models on a EPIC dataset that contains medical records from the SickKids Hospital in Toronto, Canada, and compare their performance with a number of ordinary machine learning models via an one-month-ahead evaluation scheme. We argue that these models outperform the RN Sepsis alert tools at SickKids in terms of the sensitivity for a given false positive rate of 10\%, thus showing potentials for practical benefit.


## Bayesian Additive Regression Trees for Bayesian Quadrature
_Work in progress_ \
Seth Flaxman, Zhichao Shen, Ruya Kang, Harrison Zhu, Xing Liu, Wei Jiang


## Statistical Modelling for Streaming Data
_Undergraduate Research Opportunity Programme_ \
Xing Liu; supervised by Dr Din-Houn Lau \
_Abstract_: Implementing regression models on streaming data is a popular topic in diverse areas, e.g., finance and structure engineering. This report provides a revision of a number of celebrated online regression and monitoring techniques, which are useful and popular tools for modeling streaming data. \
We begin this project by introducing the recursive least-square algorithm, together with the iterative formulae for some important goodness-of-fit measures. We then consider the problem of isolated departures (outliers) by investigating the leverage and the studentized residual. In the second part of the report, we study various change-point detection methods and develop further on the Quandt's test, followed by an analysis of their performance on both synthetic data and a chromosome study. It turns out that this newly proposed modified Quandt's test produces competitive empirical results on both experiments. \


## Stein's Paradox
_Year Two Undergraduate Research Project_ \
Hokwan Chan, Sicong Chen, Alfred Hewes, Xing Liu, Ben Tu; supervised by Professor Alastair Young \
_Abstract_: What should we do if we want to predict, say, the amount of coke consumed tomorrow in London, the number of goals scored by a football player and the  proportion of A-Level students gaining an A* in their finals? Usually, computing the averages of past events gives the most reliable guess. However, in 1955, Stein stunned the statistical world by introducing an estimator that out-performs the arithmetic mean in terms of the quadratic loss. This led to the Stein's Paradox as the estimator uses samples of independent distributions to collectively make inferences on independent parameters. \
In this project, we begin by formulating several estimators that dominate the sample mean, including the James-Stein estimator and its extensions. We then analyze how the reduction in risk varies under certain conditions to investigate which estimators are more desirable. \
By applying the estimators to a real-life example and considering the trade-off between the practicality and the effectiveness in reducing the risk value, we conclude that the so-called Positive-part James-Stein estimator is the best in most cases.
