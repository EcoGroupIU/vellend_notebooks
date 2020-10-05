# Ch. 6 Notebooks
This is a collection of python Jupyter notebook implementations of the models
described in Vellend's _Theory of Ecological Communities_ in Chapter 6
"Simulating Dynamics"

## Using the notebooks
While you can click on them in here, they don't really work. They will render
some stuff and give you nice looking formatted code but you won't be able to do
anything with them.

The best thing to do is to download them but you will need python and the
required packages installed in order to use them.

### Installing python
The easiest way to do this if you dont want to use the command line is using
Anaconda which is a really great python distribution that comes with a bunch
of useful tools. You can find the downloads for Anaconda 
[here](https://www.anaconda.com/products/individual). It looks weird and
corporate but its all open source and very chill.

If you are interested in using the command-line I'm sure you can figure it out,
seeing as you're some kind of technical computer genius.

### Installing dependencies
Once Anaconda is installed you will want to make a new `conda environment`.
This is a way of keeping all of your ducks in a row in terms of installing
packages. You can use `conda environments` for R as well, I think.

If you are on windows or don't want to use the command line I recommend using
Anaconda's graphical interface to do this.

If you are using mac or linux its really easy to do using the command line. 
You can also do it all in one step but if you're interested in that you probably
already know how this works.

First, open a terminal and make a new environment:

`conda create --name vellend_notebooks`

Now you have an environment named `vellend_notebooks`. Let's use it. We can
'go into' that environment with:

`conda activate vellend_notebooks`

Your terminal should now say `(vellend_notebooks)` and then some other stuff.
Finally, we can install the dependencies with:

`conda install numpy matplotlib tqdm jupyter ipywidgets`

This will install all of the packages that we need to run these notebooks and
everything that they depend on. It will print lots of stuff and ask you to say
`yes` at least once.

Also yes, the `numpy` core team are assholes.

### Openning the notebooks
At this point I think you can just click on them??

I usually do it through the command line by typing:

`jupyter notebooks`

when I'm in the appropriate `conda environment`. This will open a browser
window with a file browser which you can use to open the notebooks.
