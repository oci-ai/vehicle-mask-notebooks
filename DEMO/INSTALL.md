## Install Jupyter Notebook

https://jupyter.readthedocs.io/en/latest/install.html

As an existing Python user, you may wish to install Jupyter using Python’s package manager, pip, instead of Anaconda.

First, ensure that you have the latest pip; older versions may have trouble with some dependencies:

```
$ pip3 install --upgrade pip
```

Then install the Jupyter Notebook using:

```
$ pip3 install jupyter
```

```
$ git clone https://github.com/oci-ai/vehicle-mask-notebooks.git
```

## Install other environmental variables.
```
pip3 install cv2
pip3 install imageio
pip3 install numpy
pip3 install tensorflow
pip3 install matplotlib
pip3 install scipy
```

## Download Pre-Trained Model
Download pre - trained models from:
https://drive.google.com/open?id=0B6l9O8aWij8fUGtVNldUTXA4eHc

Move the models to `DEMO/salient/model`

## Start Jupyter Notebook
```
$ cd DEMO
$ jupyter notebooks
```

## Start Masking
Upload the initial car image into the `images/original/` folder

Press run or shift enter to run each cell in order.
