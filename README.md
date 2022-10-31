# Group 4 Final Project Repository

This repository hosts files that are used for Group 4's final project for the PPOL 564: Data Science I course. The repository is structured into 3 main folders,
which are listed as follows:

* **code**, which contains all the relevant scripts for data cleaning, data exploration, and producing graphs or other outputs.
* **output**, which contains all the tables, graphs and docs that are used in this project.
* **references**, which contains all codebooks and/or other reference files that are used in the final project.  

All the relevant datasets that are used in this project can be accessed in the below links:

| Dataset      		 	 | Description			   																										   				| Link 																					    |
| ----------- 		 	 | ----------- 		   																											   				| ----------- 																		        |
| sentencing_raw      	 | Raw sentencing data, downloaded from the Cook County [website](https://datacatalog.cookcountyil.gov/Courts/Sentencing/tg8v-tm6u) 			| [Link](https://drive.google.com/file/d/1rpqfudNOPpYygSTDxxj0YWuHuPIwJ9NJ/view?usp=sharing)|
| sentencing_CJARS_input | Sentencing data only containing `CASE_PARTICIPANT_ID` and `UPDATED_OFFENSE_CATEGORY` fields, as input for the CJARS offense grouping tool	| [Link](https://drive.google.com/file/d/1s5Ak5mQAKK5wypSU-ewHCh8EvuaJ3QgZ/view?usp=sharing)| 
| CJARS_results          | CJARS offense description merging results (using `sentencing_CJARS_input` as the input data) 												| [Link](https://docs.google.com/spreadsheets/d/1s77pjaPH5UU6F42RAu-DwrxcOXhFAhIA/edit?usp=sharing&ouid=107979568222729103317&rtpof=true&sd=true)|
| sentencing_analysis 	 | Sentencing data that has been pre-processed and cleaned using the `data_cleaning` ipynb code file								   			| [Link](https://drive.google.com/file/d/1rxCJdUOBRAC366GC97ZktlvrDu6epGR1/view?usp=sharing)|
