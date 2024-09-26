# SemEval2025-Task11 Submission Format Check and Evaluation Instructions


This repository contains the necessary files and instructions for participants in the SemEval2025-Task11 to check their submission and run evaluation on it.


### 1. Set Up the Required Environment

Install the required dependencies by running:

```bash
pip install -r requirements.txt

```

## 2. Prepare Your Submission File
Ensure that your submission file is properly structured and contains the required predictions using the language code as per the task. The languages are:

`afr, arq, amh, arb, ptbr, zho, eng, deu, hau, hin, ibo, ind, xho, zul, jav, kin, mar, ary, ptm, pcm, orm, ron, rus, tsn, som, spa, swa, swe, tat, tir, ukr, tso, yor`

## 3. Verify the Submission Format

To ensure your submission is valid and meets the requirements, use the `check_submission.py` script:


To verify the correctness of your submission format, run the provided Python script `check_submission.py`. This will ensure that your file adheres to the task’s requirements. Check this guide for more information about [participation and submission format](https://docs.google.com/document/d/1yETTEiD8JVL8oeXu8Dvwc7OgPIDp0ROxd9nXifsXYYE/edit) 

```bash
python check_submission.py --submission <path_to_your_submission_file>

```

This script checks for:

- Proper structure and format.
- Inclusion of predictions for all necessary languages.
- General compliance with the shared task’s requirements.

Make sure that this script runs without errors before proceeding to evaluation.

- Example for Proper formatting:  [Track A (English)](https://github.com/emotion-analysis-project/SemEval2025-Task11-Evaluation/blob/main/sample_submission_format/pred_eng_a%20copy.csv) and [Track B (German)](https://github.com/emotion-analysis-project/SemEval2025-Task11-Evaluation/blob/main/sample_submission_format/pred_eng_a%20copy.csv))


##  4. Run the Evaluation

Once the submission passes the format validation, you can proceed to evaluate its performance. This can be done by running the evaluation script provided in the Jupyter notebook `check_submission.ipynb`.


### Running the Notebook

- Open the `check_submission.ipynb` file in a Jupyter environment.
- Make sure to set the correct file paths for your submission and test data.
- Run the cells to compute the evaluation metrics (e.g., accuracy, precision, recall, F1 scores).


Alternatively, if you're running it as a script, ensure you have the necessary parameters (e.g., paths to your files).

## 5. Review Evaluation Results

After the evaluation, the script will output various metrics (see below, example for German), such as accuracy, precision, recall, and F1 scores for each language.

<img width="746" alt="image" src="assets/success-submission-sample-output.png">

Note: This is an example for Track A.

## 6. Submit to Codabench

- Zip your file by following the instructions outline [here](https://docs.google.com/document/d/1yETTEiD8JVL8oeXu8Dvwc7OgPIDp0ROxd9nXifsXYYE/edit) to submit your prediction:




