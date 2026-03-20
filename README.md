# Supplementary data for "Early nascent polypeptide dynamics are coupled to the flexibility of the ribosomal tunnel constriction"

Authors of the publication: Hugo McGrath, Michaela Černeková, Michal Kolář
All authors are affiliated with the Department of physical chemistry at the University of Chemistry and Technology, Prague, Czechia. 

The computational time by IT4Innovations is acknowledged via this mandatory statement: This work was supported by the Ministry of Education, Youth and Sports of the Czech Republic through the e-INFRA CZ (ID:90254). The 

The repository contains input files to run molecular dynamics simulations in the GROMACS program package. Furthermore, the repository includes output data and a Python scripts necessary to reproduce Figures 3, 4, 5, and 6.


## Structure
├── analyses
│   ├── output_files
│   │   ├── closest_atoms
│   │   ├── cog_dist
│   │   ├── cs_width
│   │   ├── peptide_end_to_end  # end-to-end distance
│   │   ├── polar               # polar protection
│   │   └── rmsf                # root-mean-square fluctuations
│   └── scripts                 # JupPyter lab notebooks to generate figures
├── experiments
└── simulations
    ├── ala11
    ├── ala5
    ├── empty
    ├── gly11
    ├── gly5
    └── mdp

