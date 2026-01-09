## Instructions

Download the notebook file (.ipynb) for homework assignments.

### Google Colab

The simplest way to work with the python notebook files is to use [Google Colab](https://colab.research.google.com/).
After signing up, just upload the notebook file to the colab (File>Upload Notebook). You will be able to run the script and your code on google cloud (no need for local compute).
After working on the problem, make sure you save the notebook file. It will be saved to your google drive. When you resume it, open the Colab and go to File>Open Notebook.

### Local Installation
If you want to run the program in your local computer, install python.

Then, install dependencies. If you want to use a virtual python environment, use [Anaconda](https://www.anaconda.com/download) (supports GUI) or [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) (lighter without GUI).
This is not a necessary step, but is highly recommended to make sure it does not interfere with your exisitng python installation.

```
conda create -n ece133a python=3.12
```

Then, install necessary python packages.
This will cover most of the libraries which will be used in the class.
```
pip install numpy scipy matplotlib notebook nbconvert
```

To export the notebook to pdf, you need to install [Pandoc](https://pandoc.org/installing.html). See the website for the instruction.

Command for exporting the exercise notebook file to pdf.
```
 jupyter nbconvert --to pdf FILE_NAME.ipynb
```
