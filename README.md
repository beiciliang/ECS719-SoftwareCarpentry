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
use commands to achieve a goal in a terminal session rather than opening multiple applications.

* [Version Control](https://nbviewer.jupyter.org/github/beiciliang/ECS719-SoftwareCarpentry/blob/master/Lecture-2-Version-Control.ipynb): 
keep track of changes in the source code, and make it possible for serveral people to collaboratively work on the same code base simultaneously.

* [Python](https://nbviewer.jupyter.org/github/beiciliang/ECS719-SoftwareCarpentry/blob/master/Lecture-3-Python.ipynb): 
a modern, general-purpose, object-oriented, high-level programming language, which has a strong position in scientific computing.

## Requirements

Lectures are presented using [Jupyter Notebook](http://jupyter.org/index.html), which provides a cell-based environment with great interactivity.
To open these `.ipynb` files and run the cells, the following steps are required:

### If you are using a EECS-managed desktop (Macs in G2, ITL machines, etc.):

- You don't need to install anything, just make sure you have signed up for GitHub 
(**Noted** you can use your QMUL email to get the [student developer pack](https://education.github.com) 
in order to have unlimited free private repositories).

### If you are using your own computer:

#### 1. Anaconda

- The general recommendation is that you use the Anaconda distribution to install the Jupyter Notebook, 
and other commonly used packages for scientific computing and data science. 
Please follow the instructions to [download](https://www.anaconda.com/download/) and [install](https://docs.anaconda.com/anaconda/install/) Anaconda.

#### 2. Git

- For version control, you need to install [git](http://git-scm.com/) and sign up an account at [Github](https://github.com/).

- You can then download this respository as a ZIP or clone it using `git`:
```
git clone https://github.com/beiciliang/ECS719-SoftwareCarpentry.git
```

#### 3. Getting Started With Jupyter Notebooks

- Launch the Jupyter Notebook from Anaconda Navigator, or run the following command to open up the application:
```
jupyter notebook
```

- Then you'll see the application opening in the web browser on the following address: http://localhost:8888. 

- Navigate to the *ECS719-SoftwareCarpentry* folder, open a `.ipynb` file and get started!
