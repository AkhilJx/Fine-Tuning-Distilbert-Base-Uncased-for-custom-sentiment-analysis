# Fine-Tuning-Distilbert-Base-uncased-for-custom-sentiment-analysis

This is the code for fine-tuning the Distilbert Base uncased with a custom dataset to perform sentiment analysis on a given text.


# Dataset:
Create a CSV file using the sample snippet code provided as data_preparation.ipynb file. You can also create a CSV file locally by copy-pasting the contents without code using MS Office or another application. 

The dataset contains two columns named "Text" and "Labels," where the text column contains sentences, and the label column contains the corresponding nature/sentiment. 

I have taken 3 sentiments named "positive", "negative" and "neutral", each with 100 sentences making it 300 rows.

The sentences were obtained from ChatGPT using appropriate prompts.


# Model:
The model used for fine-tuning in this code is Distilbert Base uncased. 
The documentation of the model is provided at: https://huggingface.co/distilbert/distilbert-base-uncased


# Reference:
The code was built using the code from the medium blog : 
https://brighteshun.medium.com/sentiment-analysis-part-1-finetuning-and-hosting-a-text-classification-model-on-huggingface-9d6da6fd856b

# I have pushed the model to my hugging face repo as well.
# link: 
https://huggingface.co/AkhilJX/fine-tuned-distilbert-base-uncased
