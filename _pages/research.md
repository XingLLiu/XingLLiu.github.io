---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->


# Publication
- Zhu, H., **Liu, X.**, Kang, R., Shen, Z., Flaxman, S., Briol, F-X. (2020). *Bayesian probabilistic numerical integration with tree-based models*. To appear at Neural Information Processing Systems. [*(Preprint)*](https://arxiv.org/abs/2006.05371)


# Discussion
- Zhu, H., **Liu, X**., Caron, A., Manolopoulou, I. Flaxman, S., Briol, F-X. (2020). Contributed Discussion of “Bayesian Regression Tree Models for Causal Inference: Regularization, Confounding, and Heterogeneous Effects”. Bayesian Analysis, 15(3). To appear in [*Journal (pp55-58)*](https://projecteuclid.org/euclid.ba/1580461461#abstract) [*(Preprint)*](https://fxbriol.github.io/pdfs/BART_contributed_discussion.pdf).

# Talk
- 19th Aug 2021, *Bayesian probabilistic numerical integration with tree-based models*. 13th International Conference on Monte Carlo Methods and Applications (MCM), Universität Mannheim, Germany (online).


# Research Projects
### Approximate Bayesian Computation with Optimal Transport
<span style="color:grey">_Part III Essay;_ [_link_](http://XingLLiu.github.io/files/Part_III_Essay_ABC_with_Optimal_Transport.pdf) </span><br>
**Xing Liu**; supervised by Dr. Sergio Bacallado <br>
<span style="color:grey">_Abstract:_</span>
The complexity of many real-life data generating processes either defies the access to the likelihood function or renders it too expansive to be evaluated. In this case, standard Bayesian inference techniques, such as Markov chain Monte Carlo, can no longer be used. A popular roundabout is Approximate Bayesian Computation (ABC). ABC only assumes one has a generative model from which data can be drawn. It relies on a user-specified discrepancy metric that compares some summaries of the observation and the generated data. However, an improperly selected metric or summary may bias the discrimination between models. Optimal transport (OT) metrics have recently been proposed to remedy this issue. OT metrics are flexible, admit decent convergence properties and are often able to capture all differences between distributions. In this essay, we review and compare two OT metrics and one information-based measure that arose in the ABC literature, namely the Wasserstein distances, the maximum mean discrepancy (MMD) and the Kullback-Leibler (KL) divergence. We summarize the theoretical studies of their posterior concentration in the present literature, and discuss how these metrics can be adapted to large-scale data sets. We also compare these methods through four benchmark experiments, including a real-life study on ecological dynamic systems.


### Predicting Sepsis at Triage
<span style="color:grey">_Fields Undergraduate Summer Research Program_ </span> <br>
**Xing Liu**; supervised by Dr. Anna Goldenberg and Erik Drysdale <br>
<span style="color:grey">_Abstract:_</span>
Sepsis is a lethal disease that causes millions of neonatal deaths annually, and one hour in the treatment procedure can make a huge difference for septic patients. In this regard, using machine learning approaches to help clinicans to make early Sepsis predictions has gain in popularity in recent years. Although many have shown promising predictive performance, these methods generally suffer from high false positive rates. We propose two neural network models that respectively makes use of the TF-IDF and the Clinical BERT model, and show experimentally how they could improve the predictive performance at medical triage. We train these models on a EPIC dataset that contains medical records from the SickKids Hospital in Toronto, Canada, and compare their performance with a number of ordinary machine learning models via an one-month-ahead prediction scheme. We argue that our models outperform the RN Sepsis alert tools at SickKids in terms of the sensitivity for a given false positive rate of 10%, thus showing potentials for practical benefit.

