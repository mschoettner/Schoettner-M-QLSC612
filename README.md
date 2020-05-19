# Schoettner-M-QLSC612

This repository contains the assignment for the first week of the Brainhack School.

## Installation

The code was tested on *Python 3.7.6* using *miniconda*, with the following package versions:

- pandas 1.0.3
- seaborn 0.10.0
- scipy 1.4.1

To install the packages you can use `conda` (run these commands in the shell or in an anaconda prompt if on Windows):

```
conda install pandas=1.0.3
conda install seaborn=0.10.0
conda install scipy=1.4.1
```

Alternatively, you can install them using `pip`:

```
pip install pandas==1.0.3
pip install seaborn==0.10.0
pip install scipy==1.4.1
```

You will also need jupyter, which can be installed with either `conda install -c conda-forge jupyterlab` or `pip install jupyterlab`. For further instructions see [here](https://jupyter.org/install).

## Running the code

The analysis is run in the jupyter notebook `myanalysis.ipynb`. It will generate a scatterplot of partY and VIQ and fit a linear regression for the male participants in the brainsize data set. For more information, see the comments in the notebook.

## Outputs

You should get the following outputs for the linear regression:

*partY ~ VIQ:*
- Slope: -0.3231687799523172
- P-value: 0.006498162757245594
- R-squared: 0.3793545687503652

*partY2 ~ VIQ:*
- Slope: -0.1337686512128251
- P-value: 0.3361285973253568
- R-squared: 0.057902062587242106

...and for the scatterplots:

![alt text](https://github.com/mschoettner/Schoettner-M-QLSC612/blob/master/figures/partY-VIQ-scatterplot.png)
![alt text](https://github.com/mschoettner/Schoettner-M-QLSC612/blob/master/figures/partY2-VIQ-scatterplot.png)
