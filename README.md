# ai-focused-summarization
This is the repository for the NewSum EMNLP Workshop 2021 submission "Transformer Models for Targeted Summarization of Medical Publications" 

The following files are included:

Google Colaboratory notebooks:

Fine_Tuning_BERT.ipynb / Fine_Tuning_DistilBERT.ipynb / Fine_Tuning_RoBERTa.ipynb -> fine-tuning of the LMs with full abstract input

Fine_Tuning_Single Sent.ipynb -> fine-tuning of the LMs with sentence input

DAPT_full_abstracts.ipynb -> dapt with MLM on full abstracts

DATA:

cleaned1000.json -> labeled dataset with 1000 abstracts

pubmed_papers.json -> unlabeled dataset with >31500 abstracts (zipped because of github file size restriction)
