[Analystics Vidhya](https://www.analyticsvidhya.com/blog/2017/03/imbalanced-classification-problem/?utm_source=feedburner&utm_medium=email&utm_campaign=Feed%3A+AnalyticsVidhya+%28Analytics+Vidhya%29)
<br> It has been taken from this page

How to address imbalanced data

Resampling Techniques
===================

To tackle with imbalanced data entails strategies such as improving classification algorithms or balancing classes in the training data (data preprocessing) before providing the data as input to the machine learning algorithm. The later technique is preferred as it has wider application.

The main objective of balancing classes is to either increasing the frequency of the minority class or decreasing the frequency of the majority class. This is done in order to obtain approximately the same number of instances for both the classes. Let us look at a few resampling techniques:

* Random over-sampling:  increases the number of instances in the minority class by randomly replicating them in order to present a higher representation of the minority class in the sample.

* Random under-sampling
* Cluster-based oversampling
* Informed Over Sampling
* Modified synthetic minority oversampling technique (MSMOTE)

Algorithmic Ensemble Techniques
===============================

<br> The above section, deals with handling imbalanced data by resampling original data to provide balanced classes. In this section, we are going to look at an alternate approach i.e.  Modifying existing classification algorithms to make them appropriate for imbalanced data sets.

The main objective of ensemble methodology is to improve the performance of single classifiers. The approach involves constructing several two stage classifiers from the original data and then aggregate their predictions.
 
