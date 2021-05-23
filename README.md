# Chatbot-NLU

### Knowledge Base

- Question, answer and intent tag

### NLU Pipeline

- Tokenization
- Lemmatization
- Text Cleaning

### Intent Classifier

- 3 layer linear model classifying most probable intents of given query

### Policy Maker
- Finding the best matching answer based on the high-probable intents provided by intent-classifier
- Utter some predefined responses
- Ask users for more values
- Handling out-of-scope message

### Working of the chabot

![image](https://user-images.githubusercontent.com/46133803/119264456-eef53000-bc00-11eb-9999-7bbb1f7e7620.png)
