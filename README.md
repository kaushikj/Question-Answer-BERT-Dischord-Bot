# Question-Answer-BERT-Dischord-Bot
This project is a Chatbot deployed on discord channel. It is capable of answering questions from users by scanning across databases containing millions of paragraphs. The most relevant paragraph is first filtered using a search engine based on the inverted index and then a BERT model is used to find the answer within the filtered paragraph.

## Output Screenshot
![Screenshot.png](https://github.com/kaushikj/Question-Answer-BERT-Dischord-Bot/blob/main/screenshots/discord_picture.png)

## Flowchart
![flowchart.png](https://github.com/kaushikj/Question-Answer-BERT-Dischord-Bot/blob/main/screenshots/flowchart.jpeg)

# Setting up Code
- pip install -r requirements.txt

# Files
- question_aggregate: Loads the SQuAD 2.0 dataset, converts JSON to dataframe
- question2vector: Converts Question to Vector for visualization purpose
- search_engine: An inverted index based search engine that matches the most relevent document for a given question
- bert_fine: For Training and finetuning the model
- predict_answer: A chatbot on Dischord and Final API

# Developers
- Kaushik Jeyaraman: kaushikjjj@gmail.com
- Youngheng Zou
- Hanxiao Chen
