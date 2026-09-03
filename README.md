# MSc Cybersecurity Dissertation – Web Bot Dataset Analysis

This repository contains the Python notebooks used for the practical part of my MSc Cybersecurity dissertation at Sheffield Hallam University.

The project investigates web-bot detection from a dataset-centred perspective. Instead of developing a new machine learning model, the practical work focuses on analysing and comparing datasets that represent human and automated web behaviour.

The analysis examines areas such as dataset size, class distribution, feature diversity, data quality, missing values, duplicate records, and behavioural characteristics. The results are used to support the wider dissertation investigation into how dataset characteristics may influence reported web-bot detection performance.



## Repository Contents

### `Final Dataset Analysis.ipynb`

This is the main analysis notebook used for the final dataset comparison.

It includes:

- Dataset size analysis
- Class distribution and balance
- Feature diversity
- Missing-value analysis
- Duplicate-record checks
- Descriptive statistics
- Data-quality checks
- Comparative tables
- Comparative visualisations

The prepared outputs from the other notebooks are used in this notebook for the final analysis.



### `M4D-Mouse-Move-CSV.ipynb`

This notebook processes the mouse-behaviour data from the M4D dataset.

The original M4D data is stored in JSON files together with annotation files. The notebook reads these files and prepares session-level information for further analysis.

The prepared information includes:

- Session ID
- Human or bot label
- Mouse event count
- Mouse movement duration
- Number of visited URLs
- Missing-value checks
- Duplicate checks
- Descriptive statistics

The prepared dataset is then used in the final dataset analysis.



### `Simple-Semantic-CSV.ipynb`

This notebook prepares and analyses the Simple and Semantic feature datasets.

It includes:

- Dataset structure inspection
- Session counts
- Feature counts
- Feature-type checks
- Missing-value checks
- Duplicate checks
- Descriptive statistics
- Preparation of the data for the final comparison

The Simple and Semantic feature sets describe the same underlying web sessions but represent them using different groups of features.



## Practical Workflow

The practical work follows the steps below:

1. Obtain the original research datasets.
2. Inspect the structure and contents of each dataset.
3. Process the M4D mouse-behaviour data.
4. Inspect and prepare the Simple and Semantic feature datasets.
5. Perform missing-value, duplicate, and other data-quality checks.
6. Analyse the main characteristics of each dataset.
7. Compare the datasets using tables, statistics, and visualisations.
8. Use the findings to support the discussion in the dissertation.



## Datasets

The project uses publicly available research datasets related to human and automated web behaviour.

The main data analysed in this repository includes:

- M4D mouse-behaviour data
- Simple feature dataset
- Semantic feature dataset

The original datasets are not redistributed through this repository. They should be downloaded from their original sources and used according to the licences and conditions provided by their authors.

The notebooks contain the processing and analysis steps required to prepare these datasets for the dissertation.



## Running the Notebooks

The notebooks were developed using Python in Google Colab.

To reproduce the analysis:

1. Download the required datasets from their original sources.
2. Open the required notebook in Google Colab.
3. Upload the dataset files to Colab or place them in Google Drive.
4. Update the file paths in the notebook if required.
5. Run the notebook cells in order.
6. Use the prepared outputs in `Final Dataset Analysis.ipynb`.

Some Google Drive paths used during development may need to be changed when the notebooks are run from another Google account or environment.



## Tools and Libraries

The practical analysis mainly uses:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

Additional standard Python libraries are used where required for tasks such as JSON processing, file handling, and reading dataset files.



## Outputs

The notebooks produce outputs such as:

- Prepared session-level datasets
- Dataset size summaries
- Human and bot class-distribution results
- Feature summaries
- Missing-value results
- Duplicate-record results
- Descriptive statistics
- Data-quality summaries
- Comparative tables
- Visualisations

These outputs are used to support the practical findings and discussion presented in the dissertation.



## Project Scope

The purpose of this repository is dataset characterisation and comparative analysis.

The project does not develop, train, or deploy a new web-bot detection model.

Instead, it examines how different datasets represent human and automated web behaviour and considers how characteristics such as dataset size, class balance, feature diversity, data quality, and behavioural information may influence the results reported in web-bot detection research.

The practical analysis therefore supports the wider dissertation evaluation of web-bot detection approaches from a dataset-centred perspective.



## Ethical Considerations

This project uses existing secondary research datasets and does not collect new data from human participants.

The analysis focuses on dataset characteristics and behavioural features. No attempt is made to identify individual users.

No passwords, authentication credentials, or intentionally collected personal information are included in this repository.

The original datasets remain subject to the licences and conditions provided by their respective authors. The research was carried out in accordance with the ethical requirements of the MSc Cybersecurity dissertation project at Sheffield Hallam University.



## Author

**Jeswin Thomas**  
MSc Cybersecurity  
Sheffield Hallam University  
2026
