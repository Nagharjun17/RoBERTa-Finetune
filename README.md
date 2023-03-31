# RoBerta-Finetune

The RoBERTa model was proposed in RoBERTa: A Robustly Optimized BERT Pretraining Approach by Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, Veselin Stoyanov. It is based on Google’s BERT model released in 2018.

It builds on BERT and modifies key hyperparameters, removing the next-sentence pretraining objective and training with much larger mini-batches and learning rates.

##Dataset:
AG News Dataset

##Usage
The `RoBerta_Finetune.ipynb` file can run locally through Jupyter Notebook or Google Colab.

Requirements:

Run the below command in the terminal to install dependencies.

`pip install -r requirements.txt`


##Performance and Results:

| Training	| Fully Fine-tuned RoBerta |	Frozen RoBerta |
------------|--------------------------|---------------|
| Training Loss |	0.2136 |	1.3952 |
| Training Accuracy |	92.68 |	24.15 |
| Training Precision |	93.02 |	29.11 |
| Training Recall |	93.14 |	51.23 |
| Training F1 Score |	90.08 |	15.9 |

| Testing |	Fully Fine-tuned RoBerta |	Frozen RoBerta |
----------|--------------------------|-----------------|
| Testing Loss |	0.1674 |	1.392 |
| Testing Accuracy |	94.56 |	24.13 |
| Testing Precision |	95.21 |	35.11 |
| Testing Recall |	95.52 |	71.14 |
| Testing F1 Score |	92.2 |	13.44 |


    
    
<img width="948" alt="image" src="https://user-images.githubusercontent.com/64778259/229172152-1f98751d-3017-4bce-9b48-f6496ffcc365.png">
