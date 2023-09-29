<div style="text-align: right">
    <img src="https://raw.githubusercontent.com/rcruces/2023_BigBrain_workshop_BigBrains-BrainSpaces/main/code/img/BBWS2023_cropped.png" alt="" width="1200" id="hp"/>
</div>


# 2023 HBHL BigBrain workshop: From BigBrains to BrainSpaces
# `content`
[![License: GPL v3](https://img.shields.io/github/license/rcruces/2023_BBWS_content?color=blue)](https://www.gnu.org/licenses/gpl-3.0)
[![Tutorial](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rcruces/2023_BBWS_environment/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Frcruces%252F2023_BBWS_content%26urlpath%3Dtree%252F2023_BBWS_content%252Fcode%252FBBWS2023_fromBBtoBS_Tutorial1.ipynb%26branch%3Dmain)
[![slides](https://img.shields.io/badge/launch-slices-green)](https://mybinder.org/v2/gh/rcruces/2023_BBWS_environment/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Frcruces%252F2023_BBWS_content%26urlpath%3Dtree%252F2023_BBWS_content%252Fcode%252FBBWS2023_fromBBtoBS_slices.ipynb%26branch%3Dmain)
[![env](https://img.shields.io/badge/environment-2023_BBWS-orange)](https://github.com/rcruces/2023_BBWS_environment)
[![GitHub stars](https://img.shields.io/github/stars/rcruces/2023_BBWS_content?color=brightgreen)](https://github.com/rcruces/2023_BBWS_content/stargazers)

## Installing the python environment on Linux
For Linux, if want to have the same libraries used for this tutorial installed on your system you can run:
```
wget https://raw.githubusercontent.com/rcruces/2023_BigBrain_workshop_BigBrains-BrainSpaces/main/environment.yml
conda env create -f environment.yml
```

## Installing the python environment on MacOS
For MacOSX, 
```
wget https://raw.githubusercontent.com/rcruces/2023_BigBrain_workshop_BigBrains-BrainSpaces/main/mac_env.yml
conda env create -f mac_env.yml
```
Then using `brew` install `git-annex`:
```
brew install jupyterlab
brew install datalad
pip install RISE
```
