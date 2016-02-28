# Fugue
## A Topic Modeling Package
Fugue is a research oriented topic modeling package for text mining and machine learning practitioners, designed for understanding models and algorithms. The philosophy of the package is to include mature models and algorithms that represent the state-of-the-art of research in topic modeling.

### Models/Algorithms
* latent Dirichlet allocation (LDA) with collapsed Gibbs sampling

### Prerequisites
* Gradle
* JDK
* Python 2.7

The design of the package is to limit the prerequesite packages and therefore you can easily experiment new models with minimum environments.

### How to Compile
```sh
$ ./run.sh build
```

### Run AP example
```sh
$ ./run.sh train-ap
$ ./run.sh topics-ap
```

### License
© Contributors, 2015. Licensed under an Apache-2 license.
