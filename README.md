# Self-Driving-Car-by-Udacity
Self Driving Car Challenge Participation in Udacity.

## Dependencies

* [**Tensorflow - GitHub**](https://github.com/tensorflow/tensorflow)
* [**Tensorflow**](https://www.tensorflow.org/)
* [**Keras**](https://keras.io/)
* [**OpenCV**](http://opencv.org/)
* [**NumPy**](http://www.numpy.org/)
* [**SciPy**](https://www.scipy.org/)

### Datasets

A dataset directory should have this structure:

```
  ./training_indexes.npy
  ./testing_indexes.npy
  ./validation_indexes.npy
  ./labels.npy
  ./images/
      1.png.npy
      2.png.npy
      ...
      N.png.npy
```

**Note that the image numpy files are 1-indexed.**

### Models
Some level of abstraction on top of Keras models to simplify training
and evaluating datasets, saving and loading, nesting models for
transfer learning, etc.
