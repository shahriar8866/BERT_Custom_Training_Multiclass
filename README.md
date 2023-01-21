# BERT Brands MultiClass Classification
- Develop a BERT model using BertForSequenceClassification pretrained model to classify decriptions of drinks into their brands. Since the `carbonated_soft_drinks.csv` has no label, some steps are taken in 
order to extract labels using NAMED ENTITY RECOGNITION(NER).  
- This is multi class classification task with 3 labels.
- Classification Report is presented.

# Execution
- Create a conda environment using following command: ``conda create -n <Select a Name for your Conda Env> python=3.7``
- activate your env using: `conda activate <Your Conda Env Name>`
- install ipykernal package using command: `pip install ipykernel`
- Direct to folder /bert_custom_training_multiclass and open jupyter notebook "NLP_task.ipynb".
- Execute all the cells in "NLP_task.ipynb" file one by one. 
- This notebook will save you following:
   - `branded_data.csv` which is the cleaned dataset added two columns of `brands` and `labels`.
   - `trained_bert_models` folder is created where models will be saved after each epoch.
   - `runs` folder is created which keeps the tensorboard logs for training and evaluation.

