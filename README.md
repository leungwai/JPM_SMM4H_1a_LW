# 🐤 JPM_SMM4H_1a_LW

**Subtask 1a** for the **7th Social Mining Media for Health (SMM4H)** competition hosted by **International Conference on Computational Logistics (COLING) 2022**

_by Leung Wai Liu_

This repo is training, ensembling and analysis code for the BERT Model used for Subtask 1a of the SMM4H competition that I competed in during my internship at the AI Research team in J.P. Morgan Chase in the Summer of 2022. 

_\#NLP \#BERT \#ML \#Python_

## Premise
The need to use Natural Language Processing \(NLP\) on social media posts is increasingly important as its userbase grows to guage public perception on issues, such as sentiments during the COVID-19 pandemic. 

## Task Description
Task 1 is a pharmacoviligance task, which Subtask 1A consists of classifying whether a tweet is about an adverse event of a drug or not. 

## Methodology
The datasets were trained on variants top of the BERT language model \(Devlin et al., 2019\) (RoBERTa<sub>BASE</sub>, RoBERTa<sub>LARGE</sub>, BERT<sub>BASE</sub>-uncased, BERT<sub>LARGE</sub>-uncased. 

The model ensembling code is adapted from \(Jayanthi and Gupta, 2021\) method of model ensembling. 

## Results 
| Task | F1-Score | Precision | Recall | 
| ---: | :---: | :---: | :---: |
| Task 1a | 0.838 | 0.803 | 0.877 | 

## Special Thanks
- **Akshat Gupta**, for being a great project manager and guiding us through NLP from start to finish
- **Saheed Obitayo**, for being a great manager
- **J.P. Morgan AI Research** and **Prep for Prep** for the incredible opportunity for the internship
- The organizers for the 7th SMM4H competition and 2022 COLING conference


