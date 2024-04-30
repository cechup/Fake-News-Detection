# Fake News Detection using Text Mining and Statistical Models

This repository contains the development and application of various models and methods for detecting fake news using text mining and statistical modeling approaches. It explores various machine learning techniques to classify news articles as fake or real based on their content and features, with scripts written in Python and R for data analysis and model development, as well as a comprehensive report detailing the methodologies, experiments, results, and conclusions of the project.

## Folder Contents

### Scripts
- **analisi_esplorativa.py**: Python script for exploratory data analysis of the dataset.
- **explorative_analysis.R**: R script for additional exploratory analysis and visualization.
- **models.py**: Python script containing the models used for classification and prediction.
- **NLP.py**: Python script focused on natural language processing aspects of the project.

### Data
The dataset used for training and evaluating the retrieval system can be found on Google Drive. Due to its size, it's not included directly in this repository. You can download the dataset from the following link:

[Google Drive - Dataset](https://drive.google.com/drive/folders/15m-KyHoKmaZYd-NKeBpaw3jgiX0Avvjb?usp=sharing)

Once downloaded, extract the dataset and ensure that the data paths in the scripts are correctly set to where you've stored the extracted files.

### Report
- **report.pdf**: A detailed report in PDF format that encapsulates the methodologies, experiments, results, and insights from the study.

## Experimentation Approach

The project utilizes a combination of statistical and machine learning techniques to address the challenge of fake news detection. Various models, including logistic regression, decision trees, random forests, and gradient boosting, were evaluated for their effectiveness in classifying news articles as fake or real.

## Data Setup

1. Download the dataset from the provided source.
2. Extract all the files contained in the Drive folder into a designated folder within the project directory.
3. Ensure that the data paths in the scripts are correctly set to where you've stored the extracted files.

## Requirements and Setup

This project requires Python 3.8+, R, and several dependencies listed in requirements.txt for Python and requirementsR.txt for R.

### Python Dependencies
To install the required Python packages, ensure you have Python 3.8+ installed on your system, and then run the following command:
```bash
pip install -r requirementsPy.txt
```

### R Dependencies

To install the required R packages, follow these steps:

1. **Install R:**
   - If you haven't already, download and install R from the [R Project website](https://www.r-project.org/).

2. **Install Required Packages:**
   - Open R or RStudio.
   - Run the following command to install the required packages from CRAN:
     ```R
     install.packages(c("package1", "package2", "package3"))
     ```
     Replace `"package1"`, `"package2"`, etc. with the names of the R packages listed in the `requirementsR.txt` file.

3. **Verify Installation:**
   - Once the packages are installed, you can verify that they were installed correctly by loading them in R:
     ```R
     library(package1)
     library(package2)
     ```
   - If no error messages are displayed, the packages were successfully installed.


## Running the Project
To run the project, execute the following commands in the specified order:

1. **Exploratory Data Analysis (Optional):**
   - If you wish to generate the graphs reported in the report, execute:
     ```bash
     python explorative_analysis.py
     ```

2. **NLP Analysis:**
   - Execute the text mining analysis script:
     ```bash
     python NLP.py
     ```

3. **Model Training and Evaluation:**
   - Finally, run the script for model training and evaluation:
     ```bash
     python models.py
     ```

These commands will execute the Python scripts in the specified order, allowing you to perform exploratory data analysis, NLP analysis, and model training and evaluation for the project.

## Results
Detailed results can be viewed in the report.pdf, which includes discussion on methodology, model evaluation, and conclusions based on the analysis.

## Authors
Cecilia Peccolo

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Thanks to Professor Antonio Canale for guidance and supervision throughout the project.

## Contact
For any queries, please reach out via email at peccolo.cecilia00@gmail.com.
