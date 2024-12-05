# Digits_Classification

Handwritten digits classification with a keras convnet. 

To run the notebook, the model file has to be in the same directory as the notebook in order to load the keras convnet model.

If you do not have the model file to load, then you can use the `model.py` script to build and save the convnet model for the MNIST dataset.

The notebook contains a <code>Start</code> button to open a canvas on which you can draw a number from 0 to 9. After drawing, one has to exit the canvas window by clicking <code>e</code> on the keyboard. 

The image is then processed and handed to the trained keras convnet. The prediction is shown as an browser alert popup.
