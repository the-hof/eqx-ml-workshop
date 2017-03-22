# eqx-ml-workshop
Short ML Workshop for the Equinox Innovation team

## Setup

The best way to get the dependencies and frameworks used for this workshop is by downloading Anaconda:  https://www.continuum.io/downloads

Anaconda is a python distribution that includes many data analytic libraries and toolkits (pandas, numpy, scipy, scikitlearn, statsmodels, matplotlib)

### Testing your setup

You can test whether python was correctly installed by opening a command line and typing `python`

If the install was successful, you should see the python command-line interpreter session.  You should see something like this:

```
Python 3.5.2 |Anaconda 4.3.0 (x86_64)| (default, Jul  2 2016, 17:52:12) 
[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.28)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

An additional sanity check would be to try to import the machine learning library into your interactive session:

```
import sklearn
```

If you don't get an error, your environment is set up correctly.  You can quit out of the interactive session by typing `quit()`

## Jupyter notebooks

Jupyter Notebooks are a great way to organize your analytic and machine learning research.  They serve as an interactive (almost) IDE for data analysis.  Notebooks have "cells" which can contain code or comments, and you can run cells individually including going back and rerunning previous cells.  This is really useful for testing & debugging logic, iterating over previous models to try to improve them, or refreshing data sets with new data.

You need to start a jupyter notebook server locally on your machine, and then you can use the jupyter notebooks through a web browser.  To start the server, open a command-line and type ```jupyter notebook```.  You should see some text outputting to the console as the server starts up, and a browser window should probably open.  If it doesn't, open a browser window and browse to ```http://localhost:8888/tree```

The folder that you started the notebook from in your command line window is the what Jupyter considers to be the root folder of your work.  If you cloned this repo as "eqx-ml-workshop", you can browse to that folder in the tree-view.  Once there, browse into the "notebooks" folder and click on the notebook that you want to run.  Notebooks are saved with an ".ipynb" extension.
