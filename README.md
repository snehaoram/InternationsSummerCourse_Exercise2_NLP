# Internations_Summer_Course_Exercise2_NLP

You are provided with a Python code that takes a pre-trained model called BERT (Bi-directional
Encoder Representations from Transformers) and fine-tunes it for a downstream task which is
POS tagging here. For taking a pre-trained model, it is essential to take the correct tokenizer
and model combo, and then use the custom dataset for fine-tuning. In this code, we have taken
’bert-base-uncased’ checkpoint (BERT base model) to load the tokenizer and the model.
Essential data and tags are loaded in the code. You are advised to take up the following tasks:


1. Complete two functions train() and evaluate().
2. Use different values of epoch (i.e., iterations) from the Hyper-parameter space given.
The correct output you should obtain is [a DET quick ADJ brown ADJ fox NOUN jumped VERB
over ADP the DET lazy ADJ dog NOUN]
