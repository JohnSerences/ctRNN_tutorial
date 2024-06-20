### Tutorial for basic continuous time recurrent neural network using pytorch. Train models to perform simple tasks that are commonly used in neuroscience experiments


### Recommended setup from command line (tested on Mac running Sonoma 14.5 and Python 3.9.6)
#### if you already have a full python install from Anaconda, then you can probably stay in your (base) env and may just have to install `torch` (see below)

But if you want to use a new environment, then open a terminal (command window). If you are in the `(base)` env from conda, deactivate e.g.:

`conda deactivate` 

Install virtualenv

`pip install virtualenv`

Upate pip for good luck

`python -m pip install --upgrade pip`

Create a virtualenv (calling mine pt for pytorch, but you can pick whatever name is useful for you). Think of the virtual environment like a small sandbox, and you can import only the sand toys (packages) that you want. 

`python -m venv ~/pt`

Activate the venv

`source ~/pt/bin/activate`

Install pytorch and a few other packages in the venv. We're primarily using torch (and dependencies liky numpy that are installed along with torch), but you'll need jupyter notebooks and matplotlib (for plotting results) as well

`pip install torch`

`pip install jupyter`

`pip install matplotlib`
