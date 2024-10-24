# tfm-alex-MADOBIS

Code used for analyses

All folders needed to run the code are uploaded. Their contents are classified in the following way:
/data
|- /experiment
|       |-Raw RNA-seq counts and metadata of Dianthus broteri petal tissue samples analyzed.
|- /module_gene_names
|       |-Normalized gene count data in each module detected for diploids GCN
|- exp_*
|       |-Module conservation scores obtained in experimental data analysis
     sim_*
         Module conservation scores obtained in simulated data analysis
/RData
    Modules_2p
        Output of blockwiseModule: modules obtained via hierarchical clustering in diploids
    Modules_2p_attributes
        Module structure information studied in diploids GCN
    exp_data_Zsummaries:
        Zsummaries and conservation scores obtained in experimental data analysis
    sim_data_Zsummaries:
        Zsummaries and conservation scores obtained in simulated data analysis
    /modules_exp:
        Module information and stats obtained via comparative analisis of natural and synthetic tetraploids.*
    /modules_sim:
        Module information and stats obtained via comparative analisis of simulated tetraploids.*
    /sim_datExpre:
        Simulated gene expression data.*

*= files for the smallest module are provided as an example. 
            
