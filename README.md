# Python For Astronomy #

This repository contains files that are useful for the introduction to Python, a video of the Lecture can be found here: https://www.youtube.com/watch?v=STttKxJEWKc&ab_channel=HugoPfister


## Install libraries and softwares

### Anaconda
[Go to anaconda](https://www.anaconda.com/products/individual) and follow install instructions for your OS.

If you had already installed anaconda in the past, you might want to update it:
```
conda update -n base --all
```

### Intall github
[Go to github](https://github.com/git-guides/install-git) and follow install instructions for your OS.

### Download the current repository

Open a terminal and type:

```
git clone https://github.com/HugoPfister/Python_For_Astronomy.git
```

This has the effect to *pull* (the ``git word'' for *download*) the repository containing all the data for the course.

## Check that everything went fine

### Python

If everything worked fine, in the folder in which you pulled this repository you should see the **Python_For_Astronomy** folder. To check that you have indeed installed python and dependant libraries, just type:

```
cd Python_For_Astronomy
python check.py
```

If this does not work, get in touch with me.

### Jupyter-notebook

Open a terminal and type:

```
jupyter-notebook
```

This should open an ``internet window'', if this does not happen, try to run:

```
conda install jupyter
```

Follow the instructions and try `jupyter-notebook` again. If this does not work, get in touch with me.
