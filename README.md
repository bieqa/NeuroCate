# neuroCate



Software package to adjust for unknown covariates in mass-univariate regression analyses using CATE 

The neuroCate software package provides several Matlab functions that allows the use of CATE (Confounder Adjusted Testing and Estimation). CATE is able to model unknown covariates in order to improve the control of false postive rate and family-wise error rate in mass-univariate regression analyses.

The main function to run CATE is neuroCate_cate.m, but, for new users, we recommend to first go through the script neuroCate_demo.m which describes step by step how neuroCate_cate.m can be used for an Epigenome-Wide Association Analysis (EWAS). 

Since the demo dataset is large, please request it via email bieqa@nus.edu.sg. Please see the illustration of the method in NeuroCate.pdf.

Reference:
Bryan Guillaume, Changqing Wang, Joann Poh, Mo Jun Shen, Mei Lyn Ong, Pei Fang, Neerja Karnani, Michael Meaney, Anqi Qiu*, “Improving mass-univariate analysis of neuroimaging data by modelling important unknown covariates: application to Epigenome-Wide Association Studies”, Neuroimage, 173:57-71, 2018.
