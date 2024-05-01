# ASE Project (Group 4)
```
Authors:
Sadia Afreen
Shaznin Sultana
```

## Introduction
```
This project investigates the effectiveness of Large Language Models (LLMs) in identifying source code vulnerabilities, with a focus on the latest advancements in LLM technology. Through a comparative analysis, we assess the performance of emerging LLMs specifically Llama, CodeLlama, Gemma, CodeGemma
alongside established state-of-the-art models such as BERT, RoBERTa, and GPT-3. Our study aims to shed light on the capabilities of LLMs in vulnerability detection, contributing to the enhancement of software security practices across diverse open-source repositories. We observe that CodeGemma achieves the highest F1-score of 58% and a Recall of 87%, amongst the recent additions of large language models to detect software security vulnerabilities.
```

## Source Files
```
The file hierarchy is simple enough. In *notebook_files* directory lies all the notebooks .ipynb files containing source code for fine-tuning and testing upon Llama 2, CodeLlama, Gemma, and CodeGemma. The dataset preparation files contain balancing dataset and prompt engineering, which are then exported to a gdrive location.

The *data* directory holds all the necessary data in .csv format which are created using the dataset preparation notebook files described above. These can be used directly in the fine-tuning and testing after uploading in a google drive.

The original data file is too large for github that is why the original link is given below:
https://drive.google.com/file/d/12IWKhmLhq7qn5B_iXgn5YerOQtkH-6RG/view?usp=sharing
```