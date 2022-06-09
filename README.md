# PhysiCell model builder: graphical user interface (GUI) for a PhysiCell model

VERSION: 2.4

A graphical user interface (GUI) application to make it easier to create and edit a PhysiCell (XML) model. 


## Usage
We recommend installing the [Anaconda Python distribution](https://www.anaconda.com/products/individual) to have the necessary Qt modules (used by the GUI). 
This Python distribution will also provide plotting modules that are used by the experimental Studio version of the GUI.

Download the latest release and run the following command in your Terminal (or Command Prompt) shell:
```
python bin/pmb.py  # run PhysiCell model builder
```

To run the experimental Studio version, use:
```
python bin/pmb.py --studio   # run PhysiCell model builder + "Studio" funtionality (alpha version)
```
## Release 2.4
* mostly improvements related to the Studio version, e.g.
* allow for Plotting from different output folders (rf. Config Basics)
* Warn user if SVG and full output intervals do not match
* Disable Run Simulation button when one starts
* Stop a running simulation if a new model is selected from File menu
* Provide a Legend tab to display the cell types' colors legend

## Release 2.3.1
* prevent Cell Types subtabs from scrolling away
* update VERSION and README :/

## Release 2.2.0
* provide get_pgms.sh bash script to get sample executables
* update pmb.py and run_tab.py to provide mostly-working Studio

## Release 2.1.0
* update data/interactions.xml to match PhysiCell v1.10
* provide normalize_each_gradient in motility | advanced_chemotaxis

## Release 2.0.0

This release captures most of the functionality provided in [PhysiCell 1.10.0](https://github.com/MathCancer/PhysiCell/releases/tag/1.10.0)

