# Question-Answering System Using HuggingFace Transformers

This Python script implements a question-answering system focusing on Lord Ram, a pivotal figure in Hindu mythology and the Ramayana epic, using the HuggingFace Transformers library.


**Open the Colab:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ParthaPRay/OpenAI-Chroma-Langchain/blob/main/opeai_chroma_langchain.ipynb)


## Key Components of the Script

### Library and Model Import

- The script imports `AutoModelForQuestionAnswering`, `AutoTokenizer`, and `pipeline` from the `transformers` package.
- These components are crucial for loading a pre-trained model and tokenizer and setting up a pipeline for question-answering tasks.

### Model Specification

- The script utilizes the `deepset/roberta-base-squad2` model, a RoBERTa-base model fine-tuned on the SQuAD2.0 dataset.
- SQuAD2.0 is a standard dataset for question-answering models, making this model adept at interpreting and answering natural language queries.

### Loading Model and Tokenizer

- It loads the specified pre-trained model and tokenizer.
- The model handles the understanding and answering of questions, while the tokenizer converts text inputs into a format processable by the model.

### Setting Up the Question-Answering Pipeline

- A question-answering pipeline is established using the loaded model and tokenizer.
- The pipeline is designed to accept a question and a context, process them, and generate an answer.

### Context Definition

- The script defines a context text about Lord Ram, encapsulating his importance in Hinduism, his life, and virtues.
- This context serves as the reference for answering questions about Lord Ram.

### Interactive Question-Answering Loop

- The script features an interactive loop prompting users to ask questions about Lord Ram.
- For each question, the pipeline is used to find and display the answer from the given context.
- The loop persists until the user inputs 'q' to exit.

## Conclusion

This script is a demonstration of creating a domain-specific question-answering system using advanced NLP models and techniques from the HuggingFace Transformers library.


References

1. https://www.youtube.com/watch?v=lPKEOAnMppw&ab_channel=PythonCodeCamp
