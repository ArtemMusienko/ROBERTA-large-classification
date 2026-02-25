![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=white)

# ROBERTA-large classification

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)

This code uses a **BERT-like** model - `ai-forever/ruRoberta-large`, which is located on **[HuggingFace](https://huggingface.co/ai-forever/ruRoberta-large)**.

**BERT (Bidirectional Encoder Representations from Transformers)** is a powerful natural language processing (**NLP**) model developed by **Google**. Key idea: Unlike previous models that only analyzed text from left to right or right to left, BERT is trained to understand the context of a word from both sides simultaneously.

The dataset is `data-silence/rus_news_classifier`, which is also located on **[HuggingFace](https://huggingface.co/datasets/data-silence/rus_news_classifier)**. The code includes additional data processing and filtering for the provided dataset.

*Training results:*  **loss**: 0.0159 - **categorical_accuracy**: 0.9959 - **val_loss**: 0.0632 - **val_categorical_accuracy**: 0.9889

> Highly recommend using a **T4 GPU** or more powerful!