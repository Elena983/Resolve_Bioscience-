# Resolve Bioscience
Spatial Transcriptomics 

Assessing segmentation quality of marker cells 

Pipeline via Molecular Cartography ImageJ2 plugin 
![iScreen Shoter - Google Chrome - 231109111356](https://github.com/Elena983/Resolve_Bioscience-/assets/68946912/ef398db0-4682-48ad-92ff-af0b28e1cb95)

Input
Image and gene list from Resolve

Transferring to ImageJ2 to use the Molecular Cartography plugin

Move data to QuPath for segmentation. 

Returning the segmented data to ImageJ to see cells filled with expressed genes in it

Obtaining the countmatrix from the plugin and further clustering analysis via Seurat

I produced correlation plots to see good or mixed clusters to see whether marker genes intersect in one cell.

![iScreen Shoter - Google Chrome - 231109112953](https://github.com/Elena983/Resolve_Bioscience-/assets/68946912/fbe2d44e-31ec-437e-89ce-e99aafa9ed73)

![iScreen Shoter - Google Chrome - 231109113035](https://github.com/Elena983/Resolve_Bioscience-/assets/68946912/fdd4fced-e459-43b2-b630-8218b4f47633)

I can say, watershed segmentation from QuPath is not good enough 

I would use now for the Resolve data for another segmentation algorithm, designed as an ImageJ plugin (CellPose, Stardict, etc)
