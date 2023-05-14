---
layout: single
toc: true
show_title: false
---

## [Download All BUI Data](https://www.dropbox.com/s/u8vy9vorky5oi89/Brexitb%20Uncertainty%20Index%20%28BUI%29.xlsx?dl=0) (Updated to: *December 2022*)

## News source
Our BUIs are constructed based on 11 leading UK newspapers, consistent with Baker et al. (2016):
+ The Financial Times
+ The Times
+ The Sunday Times
+ The Daily Telegraph
+ The Daily Mail and Mail on Sunday
+ The Daily Express
+ The Guardian
+ The Mirror
+ The Sun
+ The Northern Echo
+ The Evening Standard
See: Baker, S. R., Bloom, N. and Davis, S. J. (2016), ‘Measuring economic policy uncertainty’, The Quarterly Journal of Economics 131(4), 1593–163

## Methodology
+ **Aggregate BUI**

The frequency of Brexit uncertainty news proxies for Aggregate BUI. We filter out articles that touch on the topic of Brexit uncertainty from the mass of news, based on the inclusion or not of the word "Brexit" and words referring to "uncertainty" and "UK." The Word2Vec model helps by outputting the groups of words that indicate "uncertainty” and "UK.”  The term sets are:

**Uncertainty**: uncertain*; instab*; unstabl*; risk*; unpredict*; volatile*; unclear*; worry*; fear*; tension*; anxiety*; anxious*; nervous*; jitter*; unsettl*; precar*; unknow*; indecis*; angst*;
**UK**: UK (United Kingdom); British; Britain; 
Notes: asterisk means all words with the stem.

+ **Topic BUI**

The time-series share of Brexit uncertainty-related news contents devoting to each topic proxies for topic-specific Brexit uncertainty. The LDA model serves here to match the newspaper coverage to Brexit topics by identifying topics in the form of distributions over words, and subsequently, topic distribution over each news article in our news corpus.	

+ For more details, please see Section 2 in the [latest version of the paper](https://www.dropbox.com/s/9igo4cj83lohnxd/Measuring%20Brexit%20Uncertainty.pdf?dl=0). 
