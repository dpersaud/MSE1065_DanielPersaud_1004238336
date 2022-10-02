# MSE1065_DanielPersaud_1004238336
Repository to manage work related to MSE1065 - both labs and final project


The dataset I will be using for my project this semster is the Matbench v0.1 dataset (adaped from the Materials Project dataset) which contains the energy of formation for the structure of >100k materials as calcualted by DFT. 
- I found the dataset on matminer - https://hackingmaterials.lbl.gov/matminer/dataset_summary.html - DOI: 10.1063/1.4812323

This project is being developed with Kangming Li - a postdoc in my group who was able to provide me with the featurized dataset. The dataset as provided by matbench contains only 2 columns, the e_form column, which is the target variable and the structure column, which contains pymatgen structure's of the materials.
- Using these structures, pymatgen and matminer were used to generate the features (including the magpie features).

The goal of my project is to find / investiage the minimum number necessary to train a model while it still being a good (predictive and generalizable) model. This will be my own work (incolaboration with my groupmembers) so I will not be reproducing another work.



