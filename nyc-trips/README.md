# Exploring NYC trips
> **NOTE**: The current code is also available in https://github.com/ceciliassis/data-science/tree/master/nyc-trips.

## Reproducibility
In order to reproduce the study developed here, one must know a little bit about *python* and *jupyter notebook*. If you don't know anything about it, please take a look at these resources:

- https://www.dataquest.io/blog/jupyter-notebook-tutorial/
- https://www.learnpython.org/
- https://www.python.org/about/gettingstarted/

Assuming that you already know how to code in python through a jupyter notebook and uses a *UNIX based SO*  **with** python in it, let's move on.

> **IMPORTANT**: Since we are dealing with big data and `pandas`, please make sure that you have **at least** 2GB of RAM available. If you're using a UNIX based SO, you can check it using `top` command through a terminal.

### Environment setting
First, let's install `virtualenv`. With your terminal open inside _nyc-trips_ notebook's root folder, type:
```bash
python3 -m pip install virtualenv
```

Then, create a new virtual environment and activate it:
```bash
python3 -m virtualenv venv
source venv/bin/activate
```

Finally, install all needed dependencies:
```bash
pip install -r requirements.txt
```

#### Reload virtualenv
Sometimes, after installing the dependencies `jupyter notebook` doesn't find the modules. In that case all you need to do is reactivate the `virtualenv` inside the root folder, just like this:
```bash
source venv/bin/activate
```

### Execute the code
With everything set, enable `jupyter notebook` server and execute the code cells. If you don't recall how to do so, on a terminal inside notebook's root folder type:
```bash
jupyter notebook
```

After that, a new browser window will be opened and you can take from there.


