# prime-vs-base-editing

This repo contains code used to compare the capabilities of prime editing and base editing to model mutations catalogued in the MSK IMPACT dataset.

**Reference files** are too large for Github (100 Mb limit), and are available at the following dropbox repository: https://www.dropbox.com/sh/ovbpiswfghlx1j6/AABCfbBUdH-65QMzD6UyQnvwa?dl=0

Information about each notebook present in repo:

- **Genome Processing_CLEAN.ipynb:** A script that creates annotation file for genes represented in the MSK IMPACT dataset.

- **BE Coverage_CLEAN.ipynb:** A script that quantifies the capabilities of base editing (BE) to model mutations present in the MSK IMPACT dataset. Includes some figure generation as well. 

- **PE Coverage_CLEAN.ipynb:** A script that quantifies the capabilities of prime editing (PE) to model mutations present in the MSK IMPACT dataset. Includes some figure generation as well. 

- **Mouse_Human_Align_CLEAN.ipynb:** A script that generates a global pairwise alignment index between orthologous human and mouse proteins. It also generates a mapping from the DNA level to the amino acid level. The files generated in this notebook are used to determine whether a concordant mutation can be modeled in mouse in the following notebook (Mouse_Human_Mutation_Modeling_CLEAN.ipynb). 

- **Mouse_Human_Mutation_Modeling_CLEAN.ipynb:** A script that determines whether a concordant mutation can be modeled in mouse at varying stringencies/requirements for the homology of the region flanking the mutation of interest.

- **Figure creation_CLEAN.ipynb:** Contains figures generated to visualize homology, as well as other miscellaneous figures not present in PE Coverage/BE Coverage notebooks. 

For more information/inquiries, email: samgould@mit.edu or samuelgould3@gmail.com
