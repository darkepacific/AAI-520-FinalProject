# AAI-520-FinalProject
AAI-520-FinalProject

In this project, we aimed to fine-tune GPT-2 using the Cornell Movie Dialogs Corpus. We began by conducting exploratory data analysis (EDA) to identify trends and remove unnecessary data. Afterward, we preprocessed the data by cleaning the text, translating non-English entries into English, and augmenting the dataset with additional dialogues. We trained our model three different times, with the final run lasting 31 epochs. Finally, we evaluated the model on various performance metrics. While our final model exhibited some quirks, such as occasional repetition, it proved effective in generating responses that convincingly mimic movie dialogue.

# Preprocessing Steps Taken
 1. Removal of punctuation, meta data, HTML tags
 2. 5 Languages translated to English
 3. 20,000 Augmented Dialogues
 4. Removal of any dialogues under 5 characters

# Training 
 - 31 total Epochs

# Results and Conclusion
After training for 31 epochs, the chatbot demonstrated significant improvements, as reflected by strong performance across key metrics such as a BLEU score of 92.00, ROUGE-1 of 96.61, and a BERTScore F1 of 99.39, and a METEOR score of 98.39.
We believe several more rounds of training with a high number of epochs could improve the model. Additionally, sentiment analysis to filter out some of the more negative conversations, combined with additional augmentation of more mid-size dialogues, could properly tune the model for a more conversational tone.

