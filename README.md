## Overview
This project aims to evaluate the performance of various language models in generating responses to predefined prompts. The models are evaluated based on BLEU and ROUGE scores, as well as response length. Additionally, TOPSIS analysis is performed to rank the models.<br />

## Project Structure
Evaluation Script: The main script (evaluate_models.py) contains the code for evaluating the language models using BLEU, ROUGE, and TOPSIS analysis.<br />

Results: The results of the evaluation are stored in CSV files (results.csv and topsis.csv).<br />

Graphs: Bar graphs comparing TOPSIS scores and individual metrics (BLEU, ROUGE-1, ROUGE-2, ROUGE-L, and Response Length) are saved as PNG files.<br />

## Usage
1.*Install the required dependencies:*

```pip install torch transformers nltk rouge-score pandas matplotlib numpy ```

2.*Run the evaluation script:*

```python evaluate_models.py```

This script evaluates language models, performs TOPSIS analysis, and generates comparison graphs.

3.*Review Results:*

The results of the evaluation are saved in results.csv and topsis.csv.<br />
Bar graphs comparing TOPSIS scores and individual metrics are saved as PNG files.<br />


## File Descriptions
-evaluate_models.py: Main script for evaluating language models and performing analysis.
-*results.csv*: CSV file containing detailed evaluation results.<br />
-*topsis.csv*: CSV file containing TOPSIS analysis results.<br />
-*topsis_BarGraph.png*: Bar graph visualizing TOPSIS scores.<br />
![TOPSIS Bar Graph](topsis_BarGraph.png)<br />

-*ROUGE-1_comparison.png, ROUGE-2_comparison.png, ROUGE-L_comparison.png, Response Length_comparison.png*: Bar graphs comparing individual metrics.
![ROUGE-1](ROUGE-1_comparison.png)
![ROUGE-2](ROUGE-2_comparison.png)
![ROUGE-L](ROUGE-L_comparison.png)
![Response Length](<Response Length_comparison.png>)


## Dependencies
-*torch*: PyTorch library for deep learning.<br />
-*transformers*: Hugging Face Transformers library for pre-trained language models.<br />
-*nltk*: Natural Language Toolkit for BLEU score calculation.<br />
-*rouge-score*: Library for ROUGE score calculation.<br />
-*pandas*: Data manipulation library.<br />
-*matplotlib*: Plotting library.<br />
-*numpy*: Numerical computing library.<br />
