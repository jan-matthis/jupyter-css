# Jupyter CSS

A minimal stylesheet for [Jupyter](http://jupyter.org/). 

![](https://raw.githubusercontent.com/jan-matthis/jupyter-css/master/screenshot.png)

## Installation

Copy `custom.css` to the subfolder `custom` in your profile folder. By default, the profile folder is located at: `~/.jupyter/`.

### Anaconda

When using Anaconda, you might need to create a profile folder first, e.g.:
```bash
ipython profile create default
mkdir -p ~/.ipython/profile_default/static
mkdir -p ~/.ipython/profile_default/static/custom
```

In this example, you would copy `custom.css` to `~/.ipython/profile_default/static/custom/`.
