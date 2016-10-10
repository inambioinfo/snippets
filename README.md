#### Code snippets from Team-SKI @ [BioMed X](http://bio.mx/) Innovation Center, Heidelberg 
This repository contains some code snippets that demonstrate the use of RDKit, pandas, and other Python libaries for typical cheminformatics tasks.  

```
├── Cheminformatics
│   ├── Basics
│   └── Screening
├── Kinase inhibitors
├── Presentations and tutorials
│   ├── Molecular Modelling Workshop 2014
│   └── RDKit UGM 2014
│       └── rdkit_hackaton
├── Publications
└── Structural bioinformatics

```
#### Cheminformatics
##### Basics
  * ##### Scaffold analysis in Python with RDKit and pandas & Schnellkurs programming and chemoinformatics
Internal presentation given at BioMed X Team meeting, March 2014  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Scaffold%20analysis%20%26%20Schnellkurs%20in%20chemoinformatics.ipynb)

  * ##### Internal presentation on Markdown usage on our [http://bio.mx/](http://bio.mx/) web page
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Markdown%20demo.ipynb)
  * ##### Demo of proposed new functions for RDKit pandas integration
Sent on RDKit mailing list on November 2013, [merged](https://github.com/rdkit/rdkit/commit/8269bc9002cf3c6b106c847d86bcbabc016b697e) in RDKit few days later  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/RDKit%26pandas%20demo%20of%20new%20functions.ipynb)

  * ##### Custom objects and their rendering in IPython
Example of how to use object representations  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Custom%20objects%20and%20their%20rendering%20in%20IPython.ipynb)

##### Screening
  * ##### [filter_pains.py](https://github.com/Team-SKI/snippets/blob/master/Python/filter_pains.py)
Script that uses RDKit to remove PAINS compounds from sdf or smi.  
For usage info run `filter_pains.py -h`
#### Kinase inhibitors
  * ##### Kinase inhibitors - approved or in clinical trials
This notebook extracts all kinase inhibitors that are in clinical trials or on the market.  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Kinase%20inhibitors%20-%20approved%20or%20in%20clinical%20trials.ipynb)
#### Presentations and tutorials
##### Molecular Modelling Workshop 2014
  * ##### Scaffold analysis in Python with RDKit and pandas
Presentation/tutorial given at 28th Molecular Modelling Workshop, 2014 in Erlangen  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Scaffold%20analysis%20in%20Python%20with%20RDKit%20and%20pandas%20-%20MMWS%20Erlangen%202014.ipynb)
##### RDKit UGM 2014
  * ##### Scaffold analysis of ChEMBL data with pandas and RDKit
Presentation/tutorial given at [RDKit UGM](https://github.com/rdkit/UGM_2014), October 2014, Darmstadt  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/Scaffold%20analysis%20of%20ChEMBL%20data%20with%20pandas%20and%20RDKit%20-%20RDKit%20UGM2014.ipynb)
  * ##### Demo of SaveXlsxFromFrame function that can export PandasDataFrame to excel with images of mols included.  
IPython notebook: [view](http://nbviewer.ipython.org/github/Team-SKI/snippets/blob/master/IPython/rdkit_hackaton/XLSX%20export.ipynb)  
Resulting demo xlsx: [download](https://github.com/Team-SKI/snippets/blob/master/IPython/rdkit_hackaton/demo.xlsx)
#### Publications
#### Structural bioinformatics
  * ##### [prepare_for_docking.py](https://github.com/Team-SKI/snippets/blob/master/Python/prepare_for_docking.py)
Script that uses Openbabel Python bindings to generate 3D structures of compounds.  
For usage info run `prepare_for_docking.py -h`