---
title: "Final Project: Unit 11 Individual Presentation"
---

# Final Project: Unit 11 Individual Presentation

For the Unit 11 assessment I set a classical model against a neural network
for recognising pneumonia on paediatric X-rays, using the public
chest X-ray dataset of Kermany, Zhang and Goldbaum (2018). The classical
model paired gradient-orientation (HOG) features with a support vector
machine; the neural network was a small convolutional design. Both were validated with five-fold
cross-validation grouped by patient, explained with Grad-CAM and LIME, and
examined for subgroup differences and shortcut learning.

- [Analysis notebook](artefacts/unit-11-pneumonia-notebook.html)
- [Demonstration notebook](artefacts/unit-11-demonstration.html)
- [Presentation slides](artefacts/unit-11-presentation-slides.pdf)
- [Presentation transcript](artefacts/unit-11-presentation-transcript.pdf)

The complete code and the recorded presentation were submitted with the Unit 11
assessment.

## What the project found

On the held-out test set at the default threshold, the network was more accurate
than the support vector machine (0.861 against 0.777). However, a model given
only the size and shape of each image, with no pixel content at all, reached
0.829, which beat the support vector machine and came close to the network. That
result became the centre of the presentation, because it shows that a strong
score can come from how the images were collected rather than from the disease.

## Evaluation against the Unit 6 project

The tutor confirmed that the two projects were independent, so Unit 11 did not
implement the Unit 6 proposal. The fair comparison is of method, and here the
Unit 6 feedback acted as the specification for Unit 11.

| Unit 6 feedback | How Unit 11 responded |
|---|---|
| Explain why models performed differently, not only the results | Grad-CAM, LIME and a pixel-free control model tested what each model relied on |
| Discuss the limitations of the chosen algorithms | Limits were stated per model, including calibration and threshold choice |
| Justify feature and dataset choices | The dataset, features and patient grouping were each justified |
| Explain the figures | Every slide figure is interpreted in the narration |
| Cover benefits, risks and implementation | Deployment, oversight and re-validation were discussed |

Unit 6 began with a business question and moved to classical models;
Unit 11 compared classical and deep learning models directly. The main
improvement is in validation: Unit 6 adopted k-fold cross-validation part way
through, after a teammate found testing on training data, whereas Unit 11 built
patient-grouped validation in from the start and still had to correct a grouping
flaw. The remaining weakness is the same in both: the data came from one city
or one hospital, so neither result can be assumed to transfer elsewhere.

## References

Kermany, D., Zhang, K. and Goldbaum, M. (2018) _Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification_. Version 2. Mendeley Data. Available at: https://doi.org/10.17632/rscbjbr9sj.2 (Accessed: 19 October 2026).
