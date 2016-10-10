#### Code snippets from Team-SKI @ [BioMed X](http://bio.mx/) Innovation Center, Heidelberg 
This repository contains scripts & data used in publications as well as code snippets that shall demonstrate the use of RDKit, pandas, and other Python libaries for common computer-aided drug design tasks.  

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

---
#### Publications
  * **Profiling prediction of kinase inhibitors, submitted**  
 
---
#### Presentations and tutorials
##### *Molecular Modelling Workshop 2014*
  * **Scaffold analysis in Python with RDKit and pandas**  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Presentations%20and%20tutorials/Molecular%20Modelling%20Workshop%202014/Scaffold%20analysis%20in%20Python%20with%20RDKit%20and%20pandas%20-%20MMWS%20Erlangen%202014.ipynb)

##### *RDKit UGM 2014* - [RDKit UGM](https://github.com/rdkit/UGM_2014)
  * **Scaffold analysis of ChEMBL data with pandas and RDKit**  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Presentations%20and%20tutorials/RDKit%20UGM%202014/Scaffold%20analysis%20of%20ChEMBL%20data%20with%20pandas%20and%20RDKit%20-%20RDKit%20UGM2014.ipynb)

  * **hackaton**  
Demo of SaveXlsxFromFrame function that can export PandasDataFrame to Excel inclduing images of molecules**  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Presentations%20and%20tutorials/RDKit%20UGM%202014/rdkit_hackaton/XLSX%20export.ipynb)  
Resulting demo xlsx: [download](https://github.com/Team-SKI/snippets/blob/master/IPython/rdkit_hackaton/demo.xlsx)

---
#### Cheminformatics
##### *Basics*
  * **Scaffold analysis in Python with RDKit and pandas & Schnellkurs programming and chemoinformatics**  
Internal presentation given at BioMed X team meeting, March 2014  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Cheminformatics/Basics/Scaffold%20analysis%20%26%20Schnellkurs%20in%20chemoinformatics.ipynb)

  * **Internal presentation on Markdown usage**  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Cheminformatics/Basics/Markdown%20demo.ipynb)
 
  * **Demo of new functions for RDKit pandas integration; [integrated in RDKit 2013](https://github.com/rdkit/rdkit/commit/8269bc9002cf3c6b106c847d86bcbabc016b697e) **  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Cheminformatics/Basics/RDKit%26pandas%20demo%20of%20new%20functions.ipynb)

  * **Custom objects and their rendering in IPython**  
Example of how to use object representations.  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Cheminformatics/Basics/Custom%20objects%20and%20their%20rendering%20in%20IPython.ipynb)

##### *Screening*
  * **[filter_pains.py](https://github.com/Team-SKI/snippets/blob/master/Cheminformatics/Screening/filter_pains.py)**  
Script that uses RDKit to remove PAINS compounds from sdf or smile files.  
For usage info run `filter_pains.py -h`

---
#### Kinase inhibitors
  * **Kinase inhibitors - approved or in clinical trials**  
This notebook extracts all kinase inhibitors that are in clinical trials or are on the market.  
IPython notebook: [view](https://github.com/Team-SKI/snippets/blob/master/Kinase%20inhibitors/Kinase%20inhibitors%20-%20approved%20or%20in%20clinical%20trials.ipynb)

---
#### Structural bioinformatics
  * **[prepare_for_docking.py](https://github.com/Team-SKI/snippets/blob/master/Structural%20bioinformatics/prepare_for_docking.py)**  
Python script that uses Open Babel to generate 3D structures of compounds.  
For usage info run `prepare_for_docking.py -h`
