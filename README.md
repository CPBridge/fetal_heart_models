# Pre-trained Models for Fetal Heart Analysis

This repository contains pre-trained models for the algorithms contained in [this repository](https://github.com/CPBridge/fetal_heart_analysis). See that repository for further information, including a section on how to use these models. These are intended to be used as a demonstration of the algorithm.

#### Layout

This repository contains the following files:

- `structurelist` - Contains a list of structures used when training the models.
- `filter_models` - Contains particle filter definition files that define the prediction potentials.
- `forest_models` - Contains random forest models that define the observation potentials. There are several files needed to define a single model, with each performing a different task (classification or cardiac phase regression) and/or operating on different image orientations. There are two such models here, one using rotation invariant features (the `rotinv` directory) and another using rectangular features (the `rec` directory).
