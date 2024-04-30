# Fake News Detection using Text Mining and Statistical Models

This repository contains the development and application of various models and methods for detecting fake news using text mining and statistical modeling approaches. It includes scripts written in Python and R for data analysis and model development, as well as a comprehensive report detailing the methodologies, experiments, results, and conclusions of the project.

## Folder Contents

### Scripts
- **analisi_esplorativa.py**: Python script for exploratory data analysis of the dataset.
- **explorative_analysis.R**: R script for additional exploratory analysis and visualization.
- **models.py**: Python script containing the models used for classification and prediction.
- **NLP.py**: Python script focused on natural language processing aspects of the project.

### Data
- **data.zip**: Enclosed data files used in the analysis (Note: due to the potential size, this data needs to be extracted and prepared as described below).

### Report
- **report.pdf**: A detailed report in PDF format that encapsulates the methodologies, experiments, results, and insights from the study.

## Experimentation Approach

The project utilizes a combination of statistical and machine learning techniques to address the challenge of fake news detection. Various models, including logistic regression, decision trees, random forests, and gradient boosting, were evaluated for their effectiveness in classifying news articles as fake or real.

## Data Setup

1. Download the dataset from the provided source.
2. Extract data.zip into a designated folder within the project directory.
3. Ensure that the data paths in the scripts are correctly set to where you've stored the extracted files.

## Requirements and Setup

This project requires Python 3.8+, R, and several dependencies that are listed in requirements.txt.

To set up and run the project:
```bash
pip install -r requirements.txt
python analisi_esplorativa.py
Rscript explorative_analysis.R
```
# Running the Analysis
Execute each script from the command line to perform the analysis:
```
python models.py
python NLP.py
```

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
