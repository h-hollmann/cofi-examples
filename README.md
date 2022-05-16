# CoFI examples

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/inlab-geo/cofi-examples/blob/main/index.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/inlab-geo/cofi-examples/main?filepath=index.ipynb)

[CoFI](https://github.com/inlab-geo/cofi) (Common Framework for Inference) is an open-source 
initiative for interfacing between generic inference algorithms and specific geoscience problems.

This repository contains examples for running inversion algorithms using CoFI.

## Getting started

### Step 1. Get `cofi`

(Strongly recommended) Create a virtual environment to avoid conflicts with your other projects:

```console
$ conda env create -f environment.yml
$ conda activate cofi_env
```

Otherwise (if you've followed above then skip this), ensure you have `scipy` in your environment and then install `cofi` with:

```console
$ pip install cofi
```

### Step 2. Get the examples

Clone this repository:

```console
$ git clone https://github.com/inlab-geo/cofi-examples.git
```

### Step 3. Run it!

Open up Jupyter-lab:

```console
$ cd cofi-examples
$ jupyter-lab
```

Run through examples and have fun!

## Contribution

Thanks for considering contributing! You don't have to know all of the details
in order to contribute, and we welcome contributions of any forms (e.g. issues,
pull requests, etc.). If you've read the instructions below and are still unsure
where to start, feel free to contact us via [Slack](https://inlab-geo.slack.com/).

***To report bugs or typos***, please head to either [GitHub issues](https://github.com/inlab-geo/cofi-examples/issues) 
or our [Slack workspace](https://inlab-geo.slack.com/).

***To add a domain-specific (e.g. geoscience) example***, 
1. Fork this repository by clicking the button on top right
2. Clone your own version of this repository
   ```console
   $ git clone https://github.com/<your-github-id>/cofi-examples.git
   ```
   replacing `<your-github-id>` with your actual id
3. Add a working Jupyter notebook into the `notebooks/` folder
4. While experimenting with `cofi`, feel free to reference our 
   [documentation](https://cofi.readthedocs.io/en/latest/), particularly the
   [tutorials](https://cofi.readthedocs.io/en/latest/tutorial.html) and
   [example gallery](https://cofi.readthedocs.io/en/latest/cofi-examples/generated/index.html)
5. Once finished coding your notebook, commit and push your changes to your own fork
   ```console
   $ git add notebooks/<your-example-name>.ipynb notebooks/other-auxiliary-files.py
   $ git commit -m "feat: a <topic> example created by <your name>"
   $ git push origin main
   ```
   Please note that we aim to use [Angular style](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines) 
   commit messages throughout our projects
6. Head to your fork of this repository (`https://github.com/<your-github-id>/cofi-examples`),
   now you should be able to see your changes in effect. On top of your latest commit
   message, click the "Contribute" button -> "Open pull request", and write a description
   and continue as prompted
7. That's it. We will be able to see your code contribution once you've
   submitted the pull request, and will review and merge as soon as we can. Once
   approved and merged, your example will be added to CoFI 
   [example gallery](https://cofi.readthedocs.io/en/latest/cofi-examples/generated/index.html)
   automatically

## Useful resources
- InLab [website](http://www.inlab.edu.au/)
- CoFI [documentation](https://cofi.readthedocs.io/en/latest/index.html) (under construction)
- CoFI [GitHub repository](https://github.com/inlab-geo/cofi) (under construction)

## Troubleshooting for interactive lab
If you've followed the [getting started section](README.md#getting-started) above, and are still 
having trouble displaying the ipython widgets, then hopefully 
[this StackOverflow thread](https://stackoverflow.com/questions/36351109/ipython-notebook-ipywidgets-does-not-show) 
will help you. 
