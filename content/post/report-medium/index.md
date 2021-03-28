---
authors:
- admin
categories:
date: "2018-11-27T00:00:00Z"
draft: false
featured: false
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2018-11-27T00:00:00Z"
projects: []
subtitle: ""
summary: "Scientists are skeptical by nature. A scientist would pay all effort while formulating a hypothesis, setting assumptions, collecting data, analyzing it, and reporting results. Sometimes in practice, this chain of careful skeptical steps breaks, and at certain steps more than the others. Scientific literature might be less attentive when quantifying and reporting uncertainty associated with scientific results. This could be due to the rush or the lack of a proper understanding of the statistical methods. And more often, due to the over usage of some convenient methods but not others."
tags:
- Academic
- Reporting
- Statistics
title: Report in Confidence
---

Scientists are skeptical by nature. A scientist would pay all effort while formulating a hypothesis, setting assumptions, collecting data, analyzing it, and reporting results. Sometimes in practice, this chain of careful skeptical steps breaks, and at certain steps more than the others. Scientific literature might be less attentive when quantifying and reporting uncertainty associated with scientific results. This could be due to the rush or the lack of a proper understanding of the statistical methods. And more often, due to the over usage of some convenient methods but not others.

***p-value* ignores the effect size and gets smaller as a consequence of increasing the sample size**

*p-values* dominate the scientific literature as a statistical summary, reported at least once in 96% of the literature (Kyriacou 2016)⁠. a *p-value* is a probability of observing data as extreme as a test statistics when the null hypothesis is true. When this probability is very small, smaller than a predefined value, we can reject the *null* Hypothesis and consider the *alternative* true with a certain power.

One major flaw in reporting *p-value* as a sole statistical summary is that it ignores the effect size. That is the difference among averages of, say, two comparison groups in a study (*X* & *Y*). When used in hypothesis testing, *p-value* is concerned about whether there is a difference between these averages in absolute value rather than the size of this difference (*Y* — *X*). We reject the *null* hypothesis if (*Y* ≠ *X*) and we fail to reject if (*Y* =*X*) regardless the size of (*Y* — *X*) is. Here, there is a missing piece of information that we usually have to look for somewhere else in a scientific report. To get a sense of the difference between the study groups, we look at other statistical summaries like averages (mean) and standard error (SE) or standard error of the mean (SEM).

*p-value* becomes smaller as a consequence of increasing the sample size (*N*) as its denominator includes (√*N*). However, a smaller *p-value* doesn’t guarantee a better approximation of the truth but rather the a lower probability of observing the *null*. Moreover, with large samples we can detect a statistical significance of a very small size which is of no scientific meaning.

**The cut-off 0.05 is arbitrary and *p-value* is random in multiple testing**

The decision of whether to reject or fail to reject the *null* is depending on a predefined cut-off or a level of significance. Usually, we use either 0.01 or 0.05. There is nothing really special about those two numbers except for they appeared in the early papers used null hypothesis significance testing (NHST).

Following the definition of *p-value* in the context of the central limit theorem (CLT), *p-value* is the probability that a normally distributed random variable is larger, in absolute value, than the observed *t*test. So *p-value* itself is a random variable because it is dependent on a random variable. When applying multiple tests or measuring many features we get many *false positives* because of this randomness. So we should use corrections like Bonferroni (Bonferroni 1936)⁠ and don’t depend on even very small *p-values.*

**Confidence intervals provide more information and become more accurate with increasing sample sizes**

Confidence interval is a random interval with, say, a 95% probability of falling on the estimated parameter, like the average (Irizarry and Love 2015)⁠. Unlike *p-value*, confidence interval includes the observed difference, the effect size and provides a measure of uncertainty. We can obtain the same information provided by a *p-value* using the confidence interval. In a *t*test, we look for whether the averages of two groups are equals or not, so when equals, the difference will be 0. A 95% confidence interval that includes 0 implies the *p-value* should be less than 0.05.

The width of the interval reflects the effect size and this gets more accurate with increasing the sample size unlike *p-values* which become smaller when the *null* is not true as consequence. Because confidence intervals summarize the variability of the estimated value, the average, a narrow interval means a larger effect size and *vice versa*.

To sum, confidence interval provides more information than *p-value* and gets more accurate with increasing the sample size. Therefore, we recommended using confidence interval as a statistical summary.

**References**

- Bonferroni, C.E. 1936. “Teoria Statistica Delle Classi E Calcolo Delle Probabilita.”*Pubblicazioni R Istit. Super. Sci. Econ. Commer* 8: 3–62.

- Irizarry, Rafael A, and Michael I Love. 2015. *Data Analysis for the Life Sciences*. LeanPub.

- Kyriacou, DN. 2016. “The Enduring Evolution of the P Value.” *Jama* 315(11): 1113–15.