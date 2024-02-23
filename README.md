# Galactic Disk Kinematics

This repository hosts rthe example notebook used for a guest lecture on the kinemtics of stars in the Milky Way disk. Additionally, the repository contains the dependecies needed to run these notebooks.

## Installation

The dependecies for the example notebooks are saved using `poetry`. It is best practice to install the dependecies in a new enviroment. THe commands below will do this using `anaconda` to create the virtual envornment.

First, clone this repository and go to the directory contraining the files:
```
git clone https://github.com/imedan/gs_guest_lecture
cd gs_guest_lecture
```
Next, create a new environment:
```
conda create -n "GS_lect" python=3.9 ipython
```
Finally, activate the envornment and install the dependencies.
```
conda activate GS_lect
pip install poetry
poetry install --no-root
```
Now you should have all of the packages installed to run the notebooks!
