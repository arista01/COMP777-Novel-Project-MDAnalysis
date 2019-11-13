# COMP777-Novel-Project-MDAnalysis
This repository contains the code neccessary to reproduce the original MDAnalysis data as well as the file neccessary for the original data created for the novel project.
The MDAnalysis module needs to be installed either through conda or pip and the environment must be activated "source activate mdaenv".
To get the nglview module to work in Jupyter notebooks the relevent extensions must first be enabled "jupyter-nbextension enable --py --sys-prefix widgetsnbextension" and "jupyter-nbextension enable nglview --py --sys-prefix".
The PCAsuite decompression file and the PCZ compressed 1KKH file have also been uploaded. To decompress the file to a readable pdb format the shell script "$ ./pczunzip.exe --pdb -i 1kkh.backbone.1.pcz -o 1kkh.bb.1.pdb --pdb“ can be used.
