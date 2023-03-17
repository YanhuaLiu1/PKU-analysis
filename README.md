# PKU-analysis
The data and code in this repository should allow full reproduction of the data and figures discussed in the publication.

Figures with higher resolution are provided in folder 'Figures with high resolution', you can find all figures for main text and Supplementary material.

All results can be reproduced by executing the various Jupyter Python notebooks files in this order:

 1.Folder 'Model Making'    
    In this folder, we could find the code to produce model 'Recon2.2plusthreeCompetitive.json' and 'Recon2.2plusthreeIndependent.json'. And we could find the model with single compartment 'recon_2_2_simple_medium.json'. These three model could also be found in this folder.
    
 2.Folder 'PKU disease analysis with three-compartment model'   
    In this folder, we can reproduce Figure 3, Figure S7/S8/S9/S10 with 'Competition mechanism to address PKU disease in Recon2.2plusthreeCompetitive.ipynb'.
    In another Jupiter notebook 'Competition mechanism to address PKU disease in Recon2.2plusthreeIndepedent.ipynb', Figure S5 and S6 could be reproduced.
    
 3.Folder 'PKU disease analysis with a single compartment model'   
    In this folder, we could reproduce the results for PKU disease with the single compartment (Figure S1/S2/S3/S4).
    
4.Folder 'PKU diet and Obesity'   
    In this folder, the relationship between PKU diet and obesity is calculated (Also for Figure 4).
    
5.Folder 'Other potential treatments for PKU disease'   
    In this folder, we could find the potential treatments of increasing the biomass production outside of the brain and increasing the carrier ability (Also for Figure 5 and Figure S11).
    
6.Folder 'Using Recon3D'   
    We also checked the robustness of our methodology by using latest human metabolic model 'Recon3D' in this folder.
    
7.Folder 'Using tissue specific model'   
    We also checked the robustness of our methodology by using Brian and liver tissue specific model in this folder.
