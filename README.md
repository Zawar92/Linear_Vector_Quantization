## Linear_Vector_Quantization
Variants of LVQ that can be applied on multiple datasets. Prototype-based Machine Learning on Distance Data.

- MGLVQ
    - Median Variant Of GLVQ is used for classification problems. Dissimilarity information between objects is available. Probabilty function of MGLVQ is probabilistic maximizing the expectation. Prototype based vector quantizaters are used for classification of vectorial data. Using generalized EM scheme cost function of median variant of GLVQ is obtained, whereprototypes are restricted to be datapoints. It permitts the use of non-eucledian or asymmetric distances.
    - Cost Function: K(X, W) = Σlog(g+(Xi, W) + g-(Xi, W))
    - Distance Measure: Eucledian Distance results in accuracy 94 % and Levenshtein distance result in accuracy 84 %.
- MSLVQ
- LVQ

## Installation

```sh
pip install proto_dist_ml
```


```sh
- Python 3
- numpy
- scikit-learn
- scipy 
```

## Literature

Nebel, D., Hammer, B., Frohberg, K., & Villmann, T. (2015). Median variants of learning vector quantization for learning of dissimilarity data. Neurocomputing, 169, 295-305. doi:10.1016/j.neucom.2014.12.096.