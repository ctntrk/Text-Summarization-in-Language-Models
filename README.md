# Text-Summarization-in-Language-Models

A model takes a text and generates a summary based on keywords, patterns, and phrases in the text. A text can be summarized using various models. To summarize a text, the necessary libraries and models are first loaded. The text to be summarized is then provided to the model, which breaks it into smaller segments to process. Using the model, the summary is extracted and then combined to complete the summarization process. 

# Project Overview
The purpose of the code is to use these technologies and libraries to summarize a text with three different models and compare the results. The code follows these steps for each model:

- **Loading the Model:** First, the BART, T5, and PEGASUS models, along with their respective tokenizers, are loaded.
- **Tokenizing the Text:** The given text is tokenized into a format that each model can understand.
- **Summarization:** Each model generates a summary of the provided text. Strategies like beam search are used to improve the model’s performance.
- **Decoding Results:** The generated summary from each model is decoded back into text and printed on the screen.
- **Outcome:** The entire code allows you to summarize the same text using three different models and compare the summaries produced by each model. This helps users understand which model provides the most suitable results.

# Technologies Used in Project
- **Programming Language:** Python
- **Technologies:** NLP, Machine Learning, PyTorch
- ***Libraries:***
— **Basic:** NumPy, Pandas, os
— **For NLP:** Transformers (Hugging Face)
— **Transformers Dependencies:** huggingface-hub, tokenizers, safetensors, requests, tqdm, etc.
- **Models:** BART (facebook/bart-large-cnn), T5 (t5-small), PEGASUS (google/pegasus-large)
