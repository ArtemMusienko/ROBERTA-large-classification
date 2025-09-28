# ROBERTA-large classification

В данном коде используется **BERT-подобная** модель - `ai-forever/ruRoberta-large`, которая расположена на **[HuggingFace](https://huggingface.co/ai-forever/ruRoberta-large)**. 

Датасет `data-silence/rus_news_classifier`, который так же расположен на **[HuggingFace](https://huggingface.co/datasets/data-silence/rus_news_classifier)**. В коде проведена дополнительная обработка и фильтраций данных из представленного датасета. 

*Результаты обучения:*  **loss**: 0.0159 - **categorical_accuracy**: 0.9959 - **val_loss**: 0.0632 - **val_categorical_accuracy**: 0.9889

    Настоятельно рекомендую использовать графический ускоритель T4 в Google Colab!
