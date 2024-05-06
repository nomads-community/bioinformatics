# NOMADS bioinformatics
A collection of bioinformatics resources, worked examples etc built for the NOMADS project and structured as follows:

- practicals: a series of worked examples
- resources: presentations / information explaining various concepts from the Wellcome Genome Campus (WGC) or NOMADS team

## Install

#### Requirements

To install the `binfie` environemnt you will need:
- Version control software [git](https://github.com/git-guides/install-git)
- Package manager [mamba](https://github.com/conda-forge/miniforge)

#### Steps

**1.  Clone the repository from github:**
```
git clone https://github.com/nomads-community/bioinformatics
cd bioinformatics
```

**2.  Install the dependencies with mamba:**
```
mamba env create -f environment.yml
```

**3. Open the `warehouse` environment:**
```
mamba activate binfie
```

Now you will have download all the code and installed all the dependencies required.

## Running `Jupyter Notebook`

[Jupyter Notebook](https://jupyter.org/) is a great tool for exploratory data analyses. It allows you to combine blocks of code, plots, and text and equations (via markdown) into a single file called a "notebook" (more information [here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)). To launch `jupyter notebook`, navigate to the `nomads-workshop` directory and then type the following in your terminal:

```
conda activate nomads
jupyter notebook
```

A new window should open in your internet browser, allowing you to navigate the directory and open the notebooks that are stored in the `/notebooks` directory.

