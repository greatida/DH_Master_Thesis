# Narrative Analysis with Large Language Models
This repository contains data and codes for the quantitative analysis of my thesis. The quantitative analysis includes three analyses, respectively descriptive analysis, multilingual analysis and comparative analysis.

## Description of the Dataset

In the **Dataset** folder, there are three sub-folders for each analysis, including 9 csv files and 1 xlsx file. 

The xlsx is a detailed dataset where I calulate the scores of accuracy, precison, recall and F1 score through close reading. The color orange represents False Negatives, reflecting the number of narrative elements that the model predicted that were either partially accurate or missed some details. The color red represents False Positives, reflecting the number of narrative elements that the model predicted inaccurately.

**Descriptive analysis** and **Comparative analysis** used **Brahe-Novels** dataset, the secondary data sourced from the Hugging Face, a publicly available dataset stored in the public domain, with free usage and download permissions. License: cc0-1.0.

Particularly, for the **multilingual analysis**, it used primary data sourced from Archive of Our Own (AO3), the content cannot be reshared outside AO3 without consent of the authors, thus in the multilingual analysis, only links are included.

## Description of the Notebooks

In the **Notebook** folder, there are also three sub-folders for each analysis, including 10 ipynb files, recording analysis procedures comprehensively, such as creating visualizations, calculating frequencies, install the **Brahe-AWQ** LLM to output narrative elements and calculating **BERTScores**.

For example:

`Bertscore_Descriptive_Analysis` records the analysis of calculating Bertscores.

`5_14_Multilingual_Analysis` records the procedures of importing and installing "Brahe-AWQ" LLM, inputting excerpts and making it output narrative elements.

## References
Langlais, P. C. (2023, Novemeber 2).Brahe-AWQ. *Hugging Face*. https://huggingface.co/Pclanglais/Brahe-AWQ

Langlais, P. C. (2023, Novemeber 2). Brahe Novels. *Hugging Face*. https://huggingface.co/datasets/Pclanglais/Brahe-Novels

ÖzbolatText, H. (2023, September 28). Text Summarization: How to Calculate BertScore. *Medium*. https://haticeozbolat17.medium.com/text-summarization-how-to-calculate-bertscore-771a51022964#:~:text=BertScore%20is%20a%20method%20used,gram%2Dbased%20metrics%20often%20encounter
