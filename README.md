# colabcctbxsnips

On Colab, the snippets are stored in a Google Colab notebook.
See this website for an excellent introduction to CCTBX [(Computational Crystallography Toolbox)](https://cci.lbl.gov/docs/cctbx/). 
The **colabcctbxsnips** library is a collection of the code fragment to aid doing routine and not so routine computational tasks in protein crystallography. 
The URL for the snippets notebook is unused to access the snippets from a new notebook.

Click on the blue button below to open the notebook on Colab and follow the instructions at the top of the notebook on how to copy the notebook to Google Drive and then make it available to new Colab notebooks. 
This step has to be done only once. 
The snippets will be available on your next log-in; however, files and software installed on Colab with not be available on your next login to Colab.

<a href="https://colab.research.google.com/github/MooersLab/colabcctbxsnips/blob/main/colabcctbxsnips.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Local viewing

This notebook can be viewed locally in the [*nteract.app*](https://nteract.io/) -- an easy to install desktop application for viewing and editing Jupyter notebook documents (*.ipynb)--, *Jupyter Notebook*, or *Jupyter Lab*, but utilization of the **colabcctbxsnips** library requires use of Colab.

## Using a local runtime

You can use the snippet library in a Colab notebook that connected to a local runtime (i.e., a local conda env). 
See the connect pull-down for more instructions.
Basically, you have to install a Jupyter extension in the conda env that you want to use, and then you start a Jupyter session with a command like the following:

```bash
jupyter notebook \
  --NotebookApp.allow_origin='https://colab.research.google.com' \
  --port=8889 \
  --NotebookApp.port_retries=0
```

Then you copy the URL returned to the terminal by the Jupyter server and past it into the Colab notebook's connect window.
However, you still need an internet connection to connect to have Google Drive loaded so that you can access the snippet notebook.

## Sample data

Sample data files are located in the dataFiles folder.
Copy this folder to Google Drive to ease accessing the sample data on Colab.

## Related project: jupyterlabcctbxsnips

Similar snippets are available for local use in JupyterLab [jupyterlabcctbxsnips](https://github.com/MooersLab/jupyterlabcctbxsnips). 
This library is for a menu-driven snippet extension.

## Future plans:

I plan to make this library available for the Elyra snippet extension for Jupyter Lab shortly. 
It will be called taggedcctbxsnips. 
It will parallel the taggedpymolsnips library.

## Reporting errors

The CCTBX is under continuous development by a consortium of developers funded by the NIH. 
Some of the functions get renamed or deleted.
Post an issue for functions that no longer work.

## Related slides

- Colab snippet talk [ACA The Structural Science Society, 72nd Meeting, Portland, OR, 1 August 2022](https://github.com/MooersLab/ACA2022)
- GhostText talk [Oklahoma Data Science Workshop, Oklahoma City, OK, 21 July 2022](https://github.com/MooersLab/DSW22ghosttext) GhostText can be used to edit the code blocks in a computational notebook with a full-powered text editor. GhostText supports Sublime Text, VSC, Vim, Neovim, and Emacs.


## Related repos

- [easypymol](https://github.com/MooersLab/EasyPyMOL/edit/master/README.md)
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts)
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips)
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips)
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips)
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips)
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips)
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips)
- [PyMOLwallhangings](https://github.com/MooersLab/PyMOLwallhangings)

