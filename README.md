# CMS plotting recommendations and tools tutorial
This tutorial covers the main recommendations to produce production-ready CMS plots and how to do it via the two CAT-promoted plotting tools: `cmsstyle` and `mplhep`. This tutorial is divided into three different notebooks:
- [The first](1-tutorial_CAT_recommendations.ipynb) which covers recommendations and basics; 
- [The second](2-tutorial_CAT_ratioplot.ipynb) which shows a ratio plot example;
- [The third](3-tutorial_CAT_limitplot.ipynb) which shows a "Brazilian flag" limit plot example.

You can run this tutorial directly on Binder by clicking on the following widget.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ttedeschi/tutorial_CAT/HEAD?labpath=1-tutorial_CAT_recommendations.ipynb)

In case you want to run this tutorial in your own environment, the requirements are python3 and the following libraries:
```
- pip
- ROOT
- matplotlib
- scipy
- uproot
- hist
```
Beware that you can pip install directly into modern (Python3-enabled) CMSSW releases using `scram-venv`!
For a modern Python3 version (Python3.8 or greater) and PyROOT support in Python3, the minimum release cycle is `CMSSW_11_2_X`.
