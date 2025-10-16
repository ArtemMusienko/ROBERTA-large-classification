![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

# ROBERTA-large classification

В данном коде используется **BERT-подобная** модель - `ai-forever/ruRoberta-large`, которая расположена на **[HuggingFace](https://huggingface.co/ai-forever/ruRoberta-large)**. 

Датасет `data-silence/rus_news_classifier`, который так же расположен на **[HuggingFace](https://huggingface.co/datasets/data-silence/rus_news_classifier)**. В коде проведена дополнительная обработка и фильтраций данных из представленного датасета. 

*Результаты обучения:*  **loss**: 0.0159 - **categorical_accuracy**: 0.9959 - **val_loss**: 0.0632 - **val_categorical_accuracy**: 0.9889

    Настоятельно рекомендую использовать графический ускоритель T4 в Google Colab!
