kaggle_lshtc
============

Work for Kaggle's Large Scale Hierarchical Text Classification (LSHTC) Challenge


####*Data:*
* **hierachy.txt:** 863,261 lines.  Lists relations between parent and child nodes in hierarchy.
* **train.csv:** 2,365,437 lines.  Lists document vectors with multi-classes and term-frequency features.
* **train-remapped.csv:** Same as train.csv but with feature indices remapped for easier model input.
* **test.csv:** 452,168 lines.  Lists features for test set.
* **test-remapped.csv:** Same as feature index remap as training set.
* **AllZerosBenchmark.csv** Sample submission with all documents predicted in class 0.
* **KnnBaseline_3_wid.txt** Sample submission from kNN approach and 3 class precitions for each document.


