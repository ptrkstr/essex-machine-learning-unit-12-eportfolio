---
title: Practical Activities
---

# Practical Activities

Each unit's practical work is shown below as the executed notebook. A short note
records what each activity taught me, with the module learning outcomes (LO1 to
LO4, listed on the [home page](index.md#learning-outcomes)) it evidences.

## Unit 2: Exploratory data analysis

[Open the notebook](artefacts/unit-02-exploratory-data-analysis.html) · Learning outcomes: LO2

On the Auto-MPG data, the apparent regional difference in fuel economy largely
restated the effect of vehicle weight, and one-hot encoding avoided implying an
order between regions.

## Unit 3: Correlation and regression

[Open the notebook](artefacts/unit-03-correlation-and-regression.html) · Learning outcomes: LO1, LO2

Each statistic answered a narrower question than its single number suggests:
one extreme point in fourteen reversed a slope, and R squared kept rising with
polynomial degree while extrapolation became absurd.

## Unit 4: Linear regression with scikit-learn

[Open the notebook](artefacts/unit-04-linear-regression.html) · Learning outcomes: LO1, LO2, LO4

Across 212 countries, population size explained almost none of the variation in
income per head on raw values, while log and rank measures revealed a weak
negative tendency. The residual plot confirmed that a straight line was the
wrong shape for this data.

## Unit 5: Jaccard distance

[Open the notebook](artefacts/unit-05-jaccard-distance.html) · Learning outcomes: LO1, LO2

The arithmetic was simple; the encoding choices were not. They change the
distances produced from identical records, and similarity scores from health
data are inferences about real people.

## Unit 6: K-means clustering

[Open the notebook](artefacts/unit-06-k-means-clustering.html) · Learning outcomes: LO2, LO4

Standardisation moved one result far more than any setting of the algorithm. On
the unlabelled weather data, the elbow and the silhouette disagreed, which taught
me that k-means always returns tidy clusters whether or not real groups exist.

## Unit 7: Perceptron activities

[Open the notebook](artefacts/unit-07-perceptron-activities.html) · Learning outcomes: LO2

Working a perceptron by hand made its failure on XOR concrete, and the
multi-layer network resolved it. I also documented a defect that stopped a
supplied notebook from running.

## Unit 8: Gradient descent and the cost function

[Open the notebook](artefacts/unit-08-gradient-cost-function.html) · Learning outcomes: LO2

Sweeping the learning rate against the number of iterations showed that the two
settings interact, and that the fastest stable setting sits next to the one that
diverges, which is why the learning rate has to be tuned with care.

## Unit 9: CNN model activity

[Open the notebook](artefacts/unit-09-cnn-model-activity.html) · Learning outcomes: LO1

The model's errors were concentrated in classes that resemble one another, such
as cats and dogs. Read alongside Wall (2019), this showed me how uneven error
rates become an ethical problem once similar models are applied to people.

## Unit 11: Model performance measurement

[Open the notebook](artefacts/unit-11-model-performance-measurement.html) · Learning outcomes: LO1, LO3

Sweeping the metrics showed that AUC ignores the decision threshold, that R
squared is a comparison with a constant baseline rather than a percentage, and
that log loss is the measure that penalises a confident wrong answer.

## References

Wall, M. (2019) _Biased and wrong? Facial recognition tech in the dock_. Available at: https://www.bbc.com/news/business-48842750 (Accessed: 19 October 2026).
