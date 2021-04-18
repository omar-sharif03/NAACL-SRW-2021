
<img title="" src="Figures/naacl-2021.PNG" alt="">

## Emotion Classification in a Resource Constrained Language Using Transformer-based Approach

**Author:** Avishek Das, Omar Sharif, Mohammed Moshiul Hoque and Iqbal H. Sarker

**Venue:** [NAACL Student Research Workshop (SRW)-2021](https://naacl2021-srw.github.io/)

## Abstract
Although research on emotion classification has significantly progressed in high-resource languages, it is still infancy for resource-constrained languages like Bengali. However, unavailability of necessary language processing tools and deficiency of benchmark corpora makes the emotion classification task in Bengali more challenging and complicated. This work proposes a transformer-based technique to classify the Bengali text into one of the six basic emotions: anger, fear, disgust, sadness, joy, and surprise.  A Bengali emotion corpus consists of 6243 texts is developed for the classification task. Experimentation carried out using various machine learning (LR, RF, MNB, SVM), deep neural networks (CNN, BiLSTM, CNN+BiLSTM) and transformer (Bangla-BERT, m-BERT, XLM-R) based approaches. Experimental outcomes indicate that XLM-R outdoes all other techniques by achieving the highest weighted f_1-score of 69.73\% on the test data.

## Contribution

- Develop a Bengali emotion corpus consisting of 6243 text documents with manual annotation to classify each text into one of six emotion classes: anger, disgust, fear, joy, sadness, surprise. 
- Investigate the performance of various ML, DNN and transformer-based approaches on the corpus.
- Proposed a benchmark system to classify emotion in Bengali text with the experimental validation on the corpus.

## Dataset Analysis
Table 1 represents the amount of data in each class according to the train-validation-test set.

<img title="" src="Figures/train-val-test.PNG" alt="">

To get the useful insights, we investigated the train set. Statistics of the train set exhibited in table 2.

<img title="" src="Figures/statistics.PNG" alt="">

Figure 1 represents the number of texts vs the length of texts distribution for each class of the corpus.

<img title="" src="Figures/length_plot.png" alt="">

For quantitative analysis, the Jaccard similarity among the classes has been computed. We used 200 most frequent words from each emotion class, and the similarity values are reported in table 3.

<img title="" src="Figures/jaccard.PNG" alt="">

## Ackonwlegements
Without the dedication of Avishek das this work would not be possible. Thanks to [Prof. Dr. Mohammed Moshiul Hoque](https://www.researchgate.net/profile/Moshiul_Hoque) and [Dr. Iqbal H. Sarker](https://www.sites.google.com/site/iqbalsarkercse/) sir for their valuable guidance.

## Note
`If you find any anomaly or have any query/suggestion feel free to ping.`
