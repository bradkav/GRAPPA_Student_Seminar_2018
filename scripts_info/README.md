# GRAPPA Student Seminar 2018 - Scripts Info

Each group will produce a set of scripts, providing useful Dark Matter-related calculations associated with the topics we have discussed in the lectures and which you will be writing about for your reviews. The groups and topics are as follows:

* Group 1 (Cosmology): Cosmic Microwave Background (CMB) Anisotropies
* Group 2 (Candidates): Thermal freeze-out of Dark Matter particles
* Group 3 (Indirect detection): Line-of-sight integral of density squared (J-factors)
* Group 4 (Direct detection): Rates of nuclear scattering of Dark Matter Particles

Below, we give more detailed guidance concerning what we're looking for and some sensible steps to get you started. We also give some general advice for preparing and maintaining the scripts and using the GitHub repositories.

## General Advice

#### Python

The code should be written in python. If you're new to python, try looking at some of the links in [these notes](python_intro.pdf). Inevitably, you'll need to install and use the numerical and scientific libraries [NumPy](http://www.numpy.org) and [SciPy](https://www.scipy.org).

Note that there are some differences between python2 and python3 (see [here](https://wiki.python.org/moin/Python2orPython3) for a more detailed discussion). Try to stick to python3.

#### Git and GitHub

`Git` is a version control system that allows people to collaborate and merge their work more easily. In simple terms, you use `git` to keep track of changes in your code/files and to make sure that projects don't get too messy when multiple people work on them.

Projects in `git` are stored in *repositories* (like this one). We'll be storing these repositories (or 'repos') publicly on [GitHub](https://github.com). It's probably best to make an account on GitHub (for free) so that you can manage your repos more easily.

`Git` can be used from the command line or using desktop applications. There are a number of ways to learn about using `git` and `github`:

*  Tutorials and guides - [https://guides.github.com](https://guides.github.com). [This 'hello world' example](https://guides.github.com/activities/hello-world/) might be a good place to start.
*  Video guides, such as those available here: [https://www.youtube.com/user/GitHubGuides](https://www.youtube.com/user/GitHubGuides)
*  The [GitHub Learning Lab](https://lab.github.com) which guides you through some practical tutorials. See the video summary [here](https://www.youtube.com/watch?v=9S0p8YMQzsM).

#### Jupyter

[Jupyter notebooks](http://jupyter.org) are a way of combining code in python (or a couple of other languages) with plain text, LaTeX and in-line figures, so that you can present your code, calculations and research in an easily-readable format. You will need to [install jupyter notebooks](http://jupyter.org/install.html) to make use of them. (You might also be interested in using [JupyterLab](http://jupyterlab.readthedocs.io/en/stable/) as a tool for working with notebooks, but it isn't required.)

Jupyter is great, because it allows people to view your code, plots and explanations all together. You can even present Jupyter notebooks directly in a web-browser using [nbviewer](https://nbviewer.jupyter.org) - see e.g. [this notebook](https://nbviewer.jupyter.org/url/jakevdp.github.com/downloads/notebooks/XKCD_plots.ipynb). You can even let people edit and run your notebooks using [Binder](https://mybinder.org) - use [this notebook](https://mybinder.org/v2/gh/minrk/ligo-binder/master?filepath=index.ipynb) to **uncover gravitational waves** (just be patient while it loads).

**Finally, a piece of advice**: we recommend running `Cell` -> `All Output` -> `Clear` on your jupyter notebooks before you commit them to the github repo. The problem is that notebook outputs contain a lot of information in the form of text + figures and sometimes all this information doesn't play nicely with version control systems like `git`. To start with, at least, we recommend getting rid of the output before commiting to the repository. For a more detailed discussion, see e.g. [this blog post](http://timstaley.co.uk/posts/making-git-and-jupyter-notebooks-play-nice/). 


----------------

## Group 1 (Cosmology) - CMB

A good reference to start with is [arXiv:0802.3688](https://arxiv.org/abs/0802.3688). See also [this pedagogical discussion](http://background.uchicago.edu/index.html) on Wayne Hu's website. 

#### Checkpoints

#### Outputs

* Plot showing the size and shape of the acoustic oscillations in the potential, with and without baryons
* Plot showing the CMB anisotropies for a number of different 'cosmological scenarios' (no dark matter, all dark matter, no cosmological constant, etc.)

----------------

## Group 2 (Candidates) - Freeze-out

A good reference to start with is the book [Modern Cosmology (2013)](https://www.sciencedirect.com/science/book/9780122191411) by Scott Dodelson, in particular Chapter 3.

#### Checkpoints

#### Outputs

* Plot demonstrating the freeze-out process, showing the number density of particles n/T^3 as a function of the temperature of the Universe, m/T.
* Plot showing the relic abundance as a function of the particle mass and annihilation cross section.

----------------

## Group 3 (Indirect detection) - Astrophysical J-factors

A good reference to start with is [arXiv:1604.00014](https://arxiv.org/abs/1604.00014).

#### Checkpoints


#### Outputs

* A plot showing the range of possible DM density profiles near the Galactic Centre.
* A plot showing the J-factors for DM annihilation (and decay) as a function of opening angle.
* A plot comparing J-factors from different sources (Galactic Centre, Dwarf Galaxies, Clusters).

----------------

## Group 4 (Direct detection) - Nuclear recoil rates

A good reference to start with is [arXiv:1002.1912](https://arxiv.org/abs/1002.1912).

#### Checkpoints



#### Outputs

* Plot showing the Maxwell-Boltzmann velocity distribution of Dark Matter
* Plot showing the nuclear recoil spectra dR/dE for a range of nuclear targets (Xe, Ar, Ge) and for a range of DM masses
* Plot showing the total number of signal events in different detectors, as a function of energy threshold.


