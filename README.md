# GloBug
Fault localization is an important task in software debugging. Fault localization
is mostly manual in the current practice. Many methods have been
proposed over years to automate the process of fault localization. However,
the current methods only consider the local data of software system in order
to localize the root cause of a fault. In this study we introduce GloBug, which
consists of a set of methods that enable exploitation of global data (opensource
software projects) in an automated fault localization technique. In this
study we investigate two heuristics. First, we introduce GlobalBugLocator in
which we study the eect of global data on a current state-of-the-art technique
namely BugLocator. Next, we investigate the application of a Word
Embedding technique (Doc2Vec) on fault localization. Our results show that
GlobalBugLocator outperforms BugLocator with an average rate of 14% in
terms of MRR (Mean Reciprocal Rank) and MAP (Mean Average Precision)
in 64% and 54% of the cases, respectively. Also, GlobalBugLocator improves
the mean performance of BugLocator with average rates of 6.6% and 4.8% in
terms of MRR and MAP when applied to 51 software projects. This amount of
improvement is signicant compared to the improvement rates of other state-of-the-art methods. Although Word Embedding can improve the localization
accuracy in some cases, our study shows that a complex solution is not always
efective and in some cases with adding too much complexity, decreases the
performance of the simpler methods. Therefore, application of a fault localization method in a software system must be accompanied with careful analysis
and study of software characteristics.
