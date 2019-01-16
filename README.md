#  Data visualization and MLP classifier

Simple MLP classifier for particles in a specific detector (data set from http://archive.ics.uci.edu/ml/datasets/SUSY).

## ABSTRACT

This is a classification problem to distinguish between a signal process which produces supersymmetric particles and a background process which does not.

## Results

Examples of data visualization:

![sign1](https://user-images.githubusercontent.com/37218817/46367211-62faf800-c653-11e8-91d9-c360adb703fd.png)

![sign2](https://user-images.githubusercontent.com/37218817/46367268-8160f380-c653-11e8-807f-f3ee1a78d9e9.png)


## Multi-layer Perceptron Classifier:

* hidden_layer_sizes=(11,11,11,11,11)
* learning_rate_init = 0.05


```
               precision   recall  f1-score  support

        0.0       0.81      0.82      0.82    677831
        1.0       0.79      0.77      0.78    572169

avg / total       0.80      0.80      0.80   1250000

```
k-fold:

````
AUC = 0.73+-0.12
````

## Authors

* **Yuri Muller Plumm Gomes** 


## References:

* Baldi, P., P. Sadowski, and D. Whiteson. “Searching for Exotic Particles in High-energy Physics with Deep Learning.” Nature Communications 5 (July 2, 2014)
