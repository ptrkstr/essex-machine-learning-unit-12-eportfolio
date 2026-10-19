---
title: Reflective Commentary
---

# Reflective Commentary

*Organised around the three questions in Rolfe, Freshwater and Jasper (2001): what, so what and now what.*

## What happened

Over twelve units I moved from exploratory analysis and regression through clustering and neural networks to convolutional networks, language processing and model evaluation. In Unit 6, I worked in a team of five on an analysis of New York Airbnb prices for an executive audience. My contribution was organising the team, not building the models: I set up and hosted our meetings, wrote the notes for five of them, kept the task board current, reviewed pull requests and drafts, wrote the introduction and conclusion of the report and chased the final originality check and submission. The report received a distinction, together with feedback that it reported results without analysing why some models performed better than others. In Unit 11, I worked alone, testing whether a classical model or a neural network better recognises pneumonia on paediatric X-rays.

## So what

I was pleased with a distinction, but I could see what the feedback meant. We spent around three weeks on the code and only about a week on the writing, so the report described what the models did and never really asked why. My introduction framed the business question clearly, yet my conclusion mostly summarised the findings instead of challenging them. In Unit 11, I made a point of asking why at every step, which led me to test whether the models were using the images at all.

The experience of working in the team itself surprised me. I prefer working on my own, as I found in the previous module, and I was wary of a five-person team because the workload in group projects rarely ends up even. This team proved me wrong: everyone delivered their part, people reviewed each other's work properly and humour kept things relaxed while most of us juggled demanding jobs. The one thing I would change is when the writing started. We coded for three weeks first, and I think that is partly why the tutor asked for deeper critical discussion; as the author of the opening and closing sections, I could have pushed for it earlier.

The two collaborative discussions, on information system failures and on the legal and ethical side of neural networks, changed how I think about responsibility. They showed me that ethical problems in machine learning rarely come from bad intent; they come from ordinary decisions, such as which data to use or what to automate, made without looking far enough ahead. That is why, in Unit 11, I treated bias and privacy as part of the analysis from the start, which is where the first learning outcome became practical for me.

Working alone in Unit 11 produced the most uncomfortable moment of the module. I discovered a flaw in how I had split the data, which meant the results I had been pleased with could not be trusted, and much of the work had to be redone close to the deadline. My first feeling was frustration, because everything had looked so promising. However, that was the lesson: the results had looked promising because of the flaw. Zech et al. (2018) found that networks could recognise which hospital a radiograph came from, so scores measured on familiar data overstated real performance, and my flaw was a small version of that trap. Once it was corrected, I trusted the new results more, even where they were less flattering. I now see validation as the main protection against a misleading claim, which is the heart of the second and third learning outcomes.

My view of the algorithms shifted unexpectedly. I began assuming that deep learning would outperform the simpler methods in almost every case, but across the module, regression and other classical models were often competitive and considerably easier to explain. In Unit 11, the classical model was faster and simpler to justify, while the network did better on the held-out test set. That contrast showed me that the choice of algorithm is a trade-off between accuracy, cost and how convincingly a result can be justified to someone else, and the most powerful tool is not automatically the right one.

The final seminar changed how I view the course as a whole. The tutor described how his research became a product used by a real company, and his central point was to start from the problem, not the technology. It made me realise that these skills can solve real problems when applied with that discipline, and that the ethical questions we discussed become concrete the moment a system is deployed.

## Now what

The first change I will carry forward concerns teamwork. In any future team project, I will push for the writing and the critical analysis to begin in the first week alongside the technical work and treat explaining the results as a shared responsibility, not something left to whoever writes the conclusion. The organising role taught me that holding a team together is a real contribution, which is how I met the fourth learning outcome, and I would take it on again with more attention to content.

The second change concerns how I treat results. I will regard an unusually good score as a reason to investigate, by checking how the data was divided and what the model could be using before I report a number to anyone.

The third change concerns what happens after the module. My next step is to apply what I have learned to a real project of my own, starting from a problem worth solving. The most important thing this module taught me is the habit of asking why a model performs as it does, and that is the habit I intend to keep.

## References

Rolfe, G., Freshwater, D. and Jasper, M. (2001) *Critical reflection in nursing and the helping professions: a user's guide*. Basingstoke: Palgrave Macmillan.

Zech, J.R. et al. (2018) 'Variable generalization performance of a deep learning model to detect pneumonia in chest radiographs: a cross-sectional study', *PLOS Medicine*, 15(11), e1002683. Available at: https://journals.plos.org/plosmedicine/article/file?id=10.1371/journal.pmed.1002683&type=printable (Accessed: 19 October 2026).
