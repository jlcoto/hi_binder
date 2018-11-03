## README

[![Binder](https://mybinder.org/badge.svg)](https://github.com/jlcoto/hi_binder)

This repo has an example on how to run a jupyter notebook using [binder](https://github.com/jupyterhub/binderhub). You can simply click on the icon launch binder on top of the readme file. This should launch the jupyter notebook contained in this repo. You can then run the jupyter notebook as you would normally do.

If you want to run the jupyter notebook locally, then follow these instructions:

1. Clone the repo and create a virtual environment and install the requirements.

```
  $ virtualenv -p python3 venv
  $ source venv/bin/activate
  $ pip install -r requirements.txt
```

2. Launch jupyter lab.


```
  $ jupyter lab
```

Note that you might have to install the bokeh extension in order for it to run in jupyter. To install it, type the following command in your terminal:

```
  $ jupyter labextension install jupyterlab_bokeh
``` 
