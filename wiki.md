---
title: "Wiki Entry: K-Means Initialisation Sensitivity"
---

# Wiki Entry: K-Means Initialisation Sensitivity

*Unit 5.* The module wiki asked for an entry on a clustering concept, drawing on two interactive k-means visualisations, and comments on other students' entries.

## K-Means Initialisation Sensitivity

[View the entry in the module wiki](https://www.my-course.co.uk/mod/glossary/showentry.php?eid=14898&displayformat=dictionary)

The two animations make one point between them: where k-means starts decides where it ends.

Shabalin runs identical data three times, changing only the starting centroids, and gets different partitions each time. Harris lets you cause that yourself. Choosing "Uniform Points" sharpens it, because that data has no clusters at all. Placing four centroids bunched in a corner, the first pass split the points very unevenly and took several rounds to settle; spreading them to the corners split the points evenly at once and settled quickly. Both converged, to slightly different answers, on the same data.

The logic explains it. Each round only reassigns points to the nearest centroid, then moves each centroid to the mean of what it captured. Both steps are local, so neither can undo a poor start, only refine it. Convergence is guaranteed, but to a local minimum rather than the best one.

The uniform data is the uncomfortable part. There are no real groups in it, yet k-means still returns four tidy regions and reports success. It answers how to split data into k parts; it never asks whether k parts were there.

#### References

Harris, N. (2014) *Visualizing K-Means Clustering*. Available at: <https://www.naftaliharris.com/blog/visualizing-k-means-clustering/> (Accessed: 2 August 2026).

Shabalin, A. (2011) *K-means clustering*. Available at: <http://shabal.in/visuals/kmeans/1.html> (Accessed: 2 August 2026).

## Feedback received

- **Damiano** ([entry](https://www.my-course.co.uk/mod/glossary/showentry.php?eid=14898&displayformat=dictionary)): agreed that tidy k-means clusters are not evidence of real structure, and that the uniform data shows this most clearly.

## My comments on other entries

### Comment on "Weak AI" (Dzemal)

[View the entry](https://www.my-course.co.uk/mod/glossary/showentry.php?eid=14895&displayformat=dictionary)

A useful distinction to have in the glossary, and the Alexa example makes the boundary concrete. What strikes me about the weak category is how much of it depends on the task being narrow enough to specify in advance, which connects to something I ran into in the clustering activity this week: an algorithm can converge confidently on a problem nobody has checked was the right one to pose. It might be worth noting that the term is sometimes read as a judgement on capability rather than scope, when a narrow system can considerably outperform a person within its own domain. Would you say the label is about breadth rather than strength?

### Comment on "Strong AI" (Dzemal)

[View the entry](https://www.my-course.co.uk/mod/glossary/showentry.php?eid=14896&displayformat=dictionary)

The AGI and ASI split is a helpful addition, since the two often get collapsed into one another. One thing I would add is that strong AI remains a hypothetical category, unlike weak AI which describes systems already in use, so the two entries sit at rather different levels of evidence even though they read as a matched pair. That asymmetry seems worth flagging for anyone using the glossary later, because a great deal of public discussion moves between the two without marking the shift. Does the Metcalf chapter take a position on whether the transition is a matter of scale or of a different kind of architecture altogether?
