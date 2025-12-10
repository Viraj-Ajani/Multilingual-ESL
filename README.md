# Multilingual-ESL
This repo consists code of ESL paper for Indic language.

Run train_region_f30k.sh file for training.
Change argunments like data_path, data_name, logger_name, model_name, batch_size, etc. according to your convinience and in token arguments give NLP model/encoder name which uses AutoModel and AutoTokenizer.

Dataset can be found at [Kaggle](https://www.kaggle.com/datasets/kuanghueilee/scan-features).
You can translate its captions to any of the following languages Bengali, Gujarati, Hindi or Sanskrit. Alternatively, you may create a multilingual dataset by replacing four out of the five English captions with captions from each language.   

Here you can see results of different encoder on Hindi language and results of IndicBERTv2 on other languages. [Results](https://docs.google.com/spreadsheets/d/15VaCmIHcx0L_BUwY6jC4N-kZwahKaTIZgTY3LtYmU0E/edit?usp=sharing)

Due to resources limitations, models were trained on batch size of 32 or 64, however, batch size of 128 may provide better results.

To know more refer [ESL repo](https://github.com/CrossmodalGroup/ESL) provided by authors in [ESL paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10226265).
