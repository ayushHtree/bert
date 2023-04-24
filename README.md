# BERT

**This readme file only contains the changes done in the depreacted functions**

**To check the details of BERT you can checkout master branch**

## Changes done from tf1.0 deprecated functions to tf2.0
1. tf.logging -> tf.compat.v1.logging
2. tf.contrib -> tf.compat.v1.estimator
3. tf.python_io -> tf.io
4. tf.gfile -> tf.compat.v1.gfile
5. tf.FixedLenFeature -> tf.io.FixedLenFeature

### NOTE: For Flags I had performed library change from tensorflow1.0 to absl library.