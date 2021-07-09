
# Digit Recognition Training

A handwritten Digit Recognition Project, where we'll be using Keras Library to get MNIST dataset which has prebuilt train and test datasets.
To achieve this, we'll be using Convolutional Neural Network, a type of deep neural network.

## Installation

First, create and activate a virtual environment.

|For Windows|
```sh
virtualenv myenv
myenv\Scripts\activate
```
|For Linux|
```sh
virtualenv myenv
myenv/bin/activate
```

Install the dependencies and run main file.

```sh
pip install -r requirements.txt
```

## Running Locally

```sh
python main.py
```
It will create our mnist.h5 model file, which we'll load in our tkinter GUI.
When we draw something, we can send to this model for prediction.

Now it is time to run GUI, draw digit and get prediction accuracy.
Run
```sh
python tkinter_gui.py
```
![image info](https://drive.google.com/uc?export=view&id=1Hq5ZGd0G0dF70zrUzlfkofjHVhIFEXb-)

## Libraries

Following are the Libraries used in Digit recognition:

| Libraries |

 [Tkinter] [tkinter]
 [Keras] [keras]
 [Pillow] [pillow]
 [Numpy] [numpy]

#### License

MIT


   [tkinter]: <https://wiki.python.org/moin/TkInter>
   [pillow]: <https://pillow.readthedocs.io/en/stable/>
   [keras]: <https://keras.io/api/>
   [numpy]: <https://numpy.org/doc/stable/user/index.html>
   