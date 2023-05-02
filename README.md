# multiple-stimuli-rating-gui-jupyter

This Repository is meant to provide an overview of how jupyter notebook can be used to design and perform multiple stimuli listening tests. 
Jupyter with the jupyter widgets library is used to create a GUI that is then connected to the Reaper DAW by the means of the reaper API as well as the Open Sound Control (OSC) protocol. This makes it possible to create the stimuli for the test dynamically which in turn ensures easy use of headtracking and similar.

The `jupyter_GUI_minimal` notebook is a step by step tutorial on how to use the seperate elements needed and ends with a full working GUI.

The two Reaper projects provided are used by the notebook for demonstration purposes and also give an idea on how such a project needs to be structured. 

## Software / Versions
- macOS Ventura 13.1 (22C65)
- Reaper v6.64 - July 13 2022 (macOS - arm64)
- Python 3.11.0
- python-reapy 0.10.0
- python-osc 1.8.1
- ipywidgets 7.6.5
- ABComparison Plugin v1.4.0

A corresponding yml file called `msrg_env.yml` is included with the repository.

