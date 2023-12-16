# Cyberbullying Sentiment Analysis

Source code of paper "Easy Data Augmentation in Sentiment Analysis of Cyberbullying Using Support Vector Machine"

This research used dataset from previous research, can be accesed here [https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_komentar_instagram_cyberbullying.csv.](https://github.com/alwanwrwn/EDA-Cyberbullying-Sentiment-Analysis-SVM)

The research stages when training and testing are carried out with Python using scikit-learn library.

Models were trained with Python 3 runtime using Apple M1 with 8 CPU cores, 8 GPU cores, 16 neural engines, and 8 GB of RAM. To maintain consistency, we use a value of random state 42 for all models.

STEPS TO FOLLOW FOR INSTALLATION:

1. Download the git repository
2. Run the command
   pip install -r requirements.txt
3. run file training.py and training_on_twitter_dataset with command
   python training.py
   python training_on_twitter_dataset.py
