# CpG_Counter_R
Cytosine-guanine dinucleotie counter and associated data analysis for photoreceptor specific genes. 


There are three files associated with the ArcGIS StoryMap created as a requirement for JMU BIO611 Final Project guidelines to create a novel data analysis problem. The files are the: 
- Parent file containing the countCpG function
- Child file that uses the parent file countCpG function
- Miscellaneous visualization not associated with the countCpG function to graph CpG density within a specific loci

The parent file needs each chunk to be run in order for the child file to work. Please ensure the packagaes are installed and functional. The countCpG function will provide periodic updates during the analysis based on user input. 

For user input, please provide a data frame containing the gene IDs you wish to research in their respective gene symbol format. Gene symbol formats are species-specific: EX.
- Rho: Mus musculus
- RHO: Homo sapiens

The full caps version of Rho would not be recognized when analyzing a human genome. 

The countCpG function works on tidyverse commands as well as various R packages containing the reference genomes and annotations per species. The function communicates with Ensembl for the annotations. An internet connection is required to access the web-based Ensembl database. 

Each file has the R markdown (RMD) file needed to run the analysis as well as a knitted PDF of the RMD. 
