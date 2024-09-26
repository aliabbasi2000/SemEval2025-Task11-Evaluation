# SemEval2025-Task11 Evaluation 


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


To verify the correctness of your submission format, run the provided Python script `check_submission.py`. This will ensure that your file adheres to the task’s requirements. Check this guide for more information about [participation and submission format](https://docs.google.com/document/d/1yETTEiD8JVL8oeXu8Dvwc7OgPIDp0ROxd9nXifsXYYE/edit) 

```bash
python check_submission.py --submission <path_to_your_submission_file>

```

This script will validate the structure and content of the file, checking for:

- Proper formatting (check example for submission format: [Track A (English)](https://github.com/emotion-analysis-project/SemEval2025-Task11-Evaluation/blob/main/sample_submission_format/pred_eng_a%20copy.csv) and [Track B (German)](https://github.com/emotion-analysis-project/SemEval2025-Task11-Evaluation/blob/main/sample_submission_format/pred_eng_a%20copy.csv))
- Inclusion of all necessary predictions
- Compatibility with the task’s standards


##  4. Run the Evaluation


Once your submission is validated, you can proceed with evaluating your predictions. The evaluation script in `check_submission.ipynb` (Jupyter notebook) is designed to provide you with feedback on your submission.

You can execute the notebook locally or convert it into a Python script. If you're using the notebook:

- Open the notebook (check_submission.ipynb) in Jupyter.
- Make sure the correct paths to your submission and test data are set in the notebook.
- Run all cells to compute your evaluation metrics.

Alternatively, if you're running it as a script, ensure you have the necessary parameters (e.g., paths to your files).

## 5. Review Evaluation Results

After the evaluation, the script will output various metrics (see below, example for German), such as accuracy, precision, recall, and F1 scores for each language.

<img width="746" alt="image" src="assets/success-submission-sample-output.png">

Note: This is an example for Track A.

## 6. Final Checks
Before submission, double-check:

- If all checks pass, you're ready to submit your file for the final evaluation.




