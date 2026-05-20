The files in this folder are organized as follows.

Folder "code": contains the models, these are written to be run in GAMS and require the CPLEX solver

Folder "inputs": contains the input files that must be provided to GAMS
--To run the models for Section 4.1, choose one of input files 41.inc, 81.inc or 111.inc (and make the corresponding change to line 5 of the GMS code)
--To run the models for Section 4.2, choose one of input files 41.inc, 81.inc or 111.inc (and make the corresponding change to line 5 of the GMS code)
--To run the models for Section 4.3, choose one of 999a.inc, 999b.inc or 999c.inc (and rename this file "batch_data.inc"), also choose one of the "batch_subsets_100_xx_xx.inc" files from Section_4.3_subset.zip (and rename this file "batch_subsets.inc")
--To run the models for Section 4.4, choose one of 999a.inc, 999b.inc or 999c.inc (and rename this file "batch_data.inc"), also choose one of the "batch_subsets_xxxx_xxx_xx.inc" files from Section_4.4_subset.zip (and rename this file "batch_subsets.inc")

Folder "results": contains the GDX output files from each run
