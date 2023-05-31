# Using Teachable Machine image models in Python

This example comes with a model that classifies people and volleyballs, trained on about 20 images of each. To use your own model from Teachable Machine, replace the `keras_model.h5` and `labels.txt` files with your own.

This example comes with several example files which each achieve the same thing: classifying video from the webcam using a model trained with Teachable Machine.

- `google-example.py` contains the example code from the keras tab in the Export window on Teachable Machine
- `pip-example.py` contains the example code from [the python library `teachable-machine`](https://pypi.org/project/teachable-machine/)
- `tm-obj-det.py` contains the example code from [this tutorial repository](https://github.com/mjdargen/Teachable-Machine-Object-Detection)

## Running this example

Create a virtual environment and install the required packages

```
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

Then run any one of the example files, i.e.

```
python google-example.py
```
