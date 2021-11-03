This README file was generated on 2021-10-04 (2021-10-04) by Anna Maria Eilertsen.
Last updated: [2021-10-04].

-------------------
GENERAL INFORMATION
-------------------
Title of Dataset: Replication Data for: The Usability of Refactoring Tools
Ethics approval: H20-03787, RISE, UBC
Contact Information
Name: Anna Maria Eilertsen
Institution: University of Bergen
Email: anna.eilertsen@uib.no
ORCID: 0000-0002-8586-8460

Contributors: Eilertsen, Anna Maria and Murphy, Gail C. 

Description of dataset: 
This dataset contains replication artifacts related to the submitted manuscript The Usability of Refactoring Tools, by Eilertsen AM and GC. Murphy. 

The files included in the dataset allow for inspection of the coded transcripts, the codebook, and the card sorts that was undertaken for analysis. The full survey is available, as is the original tasks that the survey scenarios were based on. The raw survey results are included in an CSV format, and pre-processed versions of the results are provided along with the python script used to generate the figures seen in the paper. 

This dataset builds on previous publications by Eilertsen and Murphy [1,2]. 

--------------------
DATA & FILE OVERVIEW
--------------------
This repository has the following directory structure: 
.
├── 00_README.md
├── 0-tasks
│   ├── experiment.md
│   ├── navajo-project (folder) 
│   └── Tasks.pdf  
├── 1-coded-transcripts
│   ├── Codebook.txt
│   └── 17 x transciptIDX.csv
├── 2-cardsort
│   ├── cards (folder)
│   ├── meta-card-sort-results.csv
│   └── themes-participants-summary.csv
├── 3-survey
│   ├── raw-responses.csv
│   └── survey.pdf
└── 4-survey
    ├── csv (folder)
    └── tse_replication.ipynb

The top level folder contains folders numbered 0-4. 

Folder 0 contains the tasks that this study builds upon. the folder navajo-project contains the source code (Java 1.8, built with Maven), the file Tasks.pdf contains the participant instructions and the experiment.md file contains experimenter instructions. For a full overview of the study, refer to [1]. 

Folder 1 contains the codebook and the 17 coded transcripts that were collected during the study described in [1] and analyzed for this paper. 

Folder 2 contains the comments that we used for cards in the card sort. As there is no easy way to share the trello boards, we instead share the cvs files that we used to populate the trello boards. These are located in the cards-folder. The file meta-card-sort-results contains an overview of all the themes that we identified and the files themes-participants-summary shows how they are distributed across the participants that made the comments we used on the cards. 

Folder 3 contains the survey artifacts. The file survey.pdf contains a printed version of the full survey as shown with the preview feature on Qualtrics, and raw-responses contains all 46 responses in csv format. 

Folder 4 contains the pre-processed responses used to generate figures. The file tse_replication.ipynp contains a python notebook that is used to generate figures for the paper. This notebook can be browsed as-is or run in google colab: NB! the csv files Mapping, Participants, and Responses must be available to the script in a "data/csv/" directory. 

Within Folder 4, The folder csv contains four files used for this purpose. The file responses.csv contains all the responses with some additional calcultions used in the python script, participants.csv contains responses to the Background Questions and some simple statistics to describe participant demographics. The file mapping.csv contains strings used by the python script to look up responses to the various scenarios. The file Tableau-multiples.csv contains a simple matrix of the responses from the Tool Questions used as input to the visualization tool Tableau to generate the multiples visualization in the paper. 
 

[1] Eilertsen AM and GC. Murphy, (2021), A Study of Refactorings During Software Change Tasks, Journal of Software Evolution and Process, 2021; Special Edition, DOI: 10.1002/SMR.2378
[2] Eilertsen AM and GC. Murphy, "The Usability (or Not) of Refactoring Tools," 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), 2021, pp. 237-248, doi: 10.1109/SANER50967.2021.00030.

--------------------------
SHARING/ACCESS INFORMATION
--------------------------
Licenses/Restrictions: To be added 
Recommended citation: To be added 