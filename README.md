Hi Mr./Ms. Examiner,


#### How to clone the Git Repo 

1. 
2.
3.

#### Installing condas for package management

1.
2.
3.


#### How to recreate my condas environment

- Navigate to the path where you cloned submission_final folder from the repo link
- conda env create -f environment.yml
- Activate the environment in terminal: conda activate submission_final
	- You can also activate the condas environment from within VS code or any other notebook editor locally on your machine

#### Dependencies not covered by my condas environment

- RSQLite 2.3.5
- Install it by:
	- conda activate submission_final
	- Type the letter R and press enter in terminal
	- install.packages('RSQLite')
	
- (Recommended!) Install the latest version of Rstudio from https://posit.co/download/rstudio-desktop/ 



#### How to seamlessly run the notebooks:

1. Download or Copy the Harvard Dataverse .csv files (>12GB of data) into the empty raw_data folder (https://doi.org/10.7910/DVN/HG7NV7 - there are 26 individual files in total)
2. Navigate to python_notebooks folder and run the 2DBSetup_python.ipynb notebook or navigate to r_notebooks folder and run the 2DBsetup_R_notebook.Rmd notebook to setup the comp97to07.db database...



#### Directory Structure

submission_final/
├── python_notebooks/
│   ├── requirements.txt
│   ├── 1A_python.ipynb
│   ├── 1B_python.ipynb
│   ├── 2A_python.ipynb
│   ├── 2B_python.ipynb
│   ├── 2C_python.ipynb
│   ├── 2DBsetup_python.ipynb
│   └── py_images
├── r_notebooks/
│   ├── renv.lock
│   ├── 1A_R_notebook_.Rmd
│   ├── 1B_R_notebook_.Rmd
│   ├── 2A_R_notebook_.Rmd
│   ├── 2B_R_notebook_.Rmd
│   ├── 2C_R_notebook_.Rmd
│   ├── 2DBsetup_R_notebook_.Rmd
│   └── r_images
├── raw_data/
│   └── (Detailed instructions to access or download data into the raw_data folder)
└── README.md
