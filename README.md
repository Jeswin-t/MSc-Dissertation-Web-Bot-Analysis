# MSc Cybersecurity Dissertation – Web Bot Dataset Analysis

This repository contains the Python notebooks used for the practical component of my MSc Cybersecurity dissertation at Sheffield Hallam University.

The project investigates web-bot detection from a dataset-centred perspective. The practical analysis focuses on how datasets represent human and automated web behaviour, including dataset size, class distribution, feature diversity, data quality and behavioural characteristics.

The practical work does not develop a new web-bot detection model. Instead, it analyses and compares the datasets used in the study and supports the wider evaluation presented in the dissertation.



## Repository Contents

### Final Dataset Analysis.ipynb

This is the main analysis notebook.

It performs the final dataset characterisation and comparison, including:

- Dataset size
- Class distribution and balance
- Feature diversity
- Missing values
- Duplicate records
- Descriptive statistics
- Data-quality checks
- Comparative visualisations

### M4D-Mouse-Move-CSV.ipynb

This notebook processes the mouse-behaviour data from the M4D dataset.

It reads the original JSON and annotation files and prepares session-level information such as:

- Session ID
- Human/bot label
- Mouse event count
- Mouse movement duration
- Number of visited URLs
- Missing and duplicate checks
- Descriptive statistics

The prepared output is used in the final analysis.

### Simple-Semantic-CSV.ipynb

This notebook prepares and analyses the Simple and Semantic feature datasets.

It includes:

- Dataset structure inspection
- Session and feature counts
- Feature-type checks
- Missing-value checks
- Duplicate checks
- Descriptive statistics
- Preparation for the final comparison

The Simple and Semantic feature sets describe the same underlying sessions using different groups of features.


## Practical Workflow

The practical work follows this general process:

1. Obtain the original research datasets.
2. Inspect the dataset structure.
3. Prepare the M4D mouse-behaviour data.
4. Inspect and prepare the Simple and Semantic feature data.
5. Perform data-quality checks.
6. Analyse dataset characteristics.
7. Compare the datasets in the final analysis notebook.



## Datasets

The project uses publicly available research datasets relating to human and automated web behaviour.

The original datasets are not redistributed through this repository. They should be downloaded from their original sources and remain subject to the licences and conditions provided by their respective authors.

The notebooks contain the processing and preparation steps required for the dissertation analysis.



## Running the Notebooks

The notebooks were developed using Python in Google Colab.

To reproduce the analysis:

1. Download the required datasets from their original sources.
2. Open the relevant notebook in Google Colab.
3. Place the required dataset files in Google Drive or upload them to Colab.
4. Update the file paths where necessary.
5. Run the notebook cells in order.
6. Use the prepared datasets in `Final Dataset Analysis.ipynb`.

Some Google Drive file paths may need to be changed when running the notebooks from another account.



## Tools and Libraries

The analysis mainly uses:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

Additional Python libraries are used where required for file handling and JSON processing.



## Outputs

The notebooks produce outputs including:

- Prepared session-level datasets
- Dataset size summaries
- Class-distribution results
- Feature summaries
- Missing-value and duplicate checks
- Descriptive statistics
- Comparative tables
- Visualisations

These outputs support the practical findings reported in the dissertation.



## Scope

This repository supports dataset characterisation and comparative analysis.

It does not represent the development or deployment of a new web-bot detection system. The practical work is intended to examine dataset characteristics and support the wider dissertation investigation into how datasets may influence reported web-bot detection results.



## Author

**Jeswin Thomas**  
MSc Cybersecurity  
Sheffield Hallam University  
2026
