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

```
$ cd DEMO

$ jupyter notebooks
```

Upload the initial car image into the `images/original/` folder

Download pre - trained models from:
https://drive.google.com/open?id=0B6l9O8aWij8fUGtVNldUTXA4eHc

Move the models to DEMO/salient/model




git filter-branch --force --index-filter \
'git rm --cached --ignore-unmatch DEMO/salient/model/model.ckpt-200.data-00000-of-00001' \
--prune-empty --tag-name-filter cat -- --all
