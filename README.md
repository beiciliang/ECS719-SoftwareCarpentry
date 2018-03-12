# ECS719-SoftwareCarpentry

Resources for the software carpentry class of ECS719 Research Method I at Queen Mary University of London.

They are based on the following softwares and their corresponding versions.

Software | Version
------------ | -------------
Python | 2.7.14 64bit
IPython | 5.3.0
OS | Darwin 15.6.0 x86_64 i386 64bit

## Index

* [The UNIX Shell](https://nbviewer.jupyter.org/github/beiciliang/ECS719-SoftwareCarpentry/blob/master/Lecture-1-The-UNIX-Shell.ipynb): 
use commands to achieve a goal in a terminal session rather than opening multiple applications

* [Version Control](https://nbviewer.jupyter.org/github/beiciliang/ECS719-SoftwareCarpentry/blob/master/Lecture-2-Version-Control.ipynb): 
keep track of changes in the source code, and make it possible for serveral people to collaboratively work on the same code base simultaneously.

* [Python](https://nbviewer.jupyter.org/github/beiciliang/ECS719-SoftwareCarpentry/blob/master/Lecture-3-Python.ipynb): 
a modern, general-purpose, object-oriented, high-level programming language, which has a strong position in scientific computing.

## Requirements

Lectures are presented using [Jupyter Notebook](http://jupyter.org/index.html), which provides a cell-based environment with great interactivity.
To open these `.ipynb` files and run the cells on your own computer, the following steps are required:

1. Check if you already have Python 2 and pip installed

- Start a terminal session: 
in **Finder**, open the **Application** -> **Utilities** folder, double-click **Terminal**.

- Enter `python` and press return. 
If you see a response from a Python interpreter it will include a version number in its initial display.
If not, see the [Python downloads](https://www.python.org/downloads/) page for the most up to date versions of Python 2 to install.

- pip is already installed if you're using Python 2 >=2.7.9, but you'll need to upgrade pip.
```
pip install -U pip setuptools
```

2. Install Jupyter Notebook
The general recommendation is that you use the Anaconda distribution to install the Jupyter Notebook, 
and other commonly used packages for scientific computing and data science. 
The advantage of Anaconda is that you have access to over 720 packages that can easily be installed with Anaconda's conda, 
a package, dependency, and environment manager. 
You can download and follow the instructions for the installation of Anaconda [here](https://www.anaconda.com/download/).

If you don't want to install Anaconda, you can also install Jupyter with pip.
Just run the command line:
```
pip install jupyter
```

3. Install git

- For version control, we need to download git [here](http://git-scm.com/).

- You can then download this respository using `git` by running the command line:
```
git clone https://github.com/beiciliang/ECS719-SoftwareCarpentry.git
```

4. Getting Started With Jupyter Notebooks

- Run the following command to open up the application:
```
jupyter notebook
```

- Then you'll see the application opening in the web browser on the following address: http://localhost:8888. 

- Navigate to the ECS719-SoftwareCarpentry folder, open a `.ipynb` file and get started!
