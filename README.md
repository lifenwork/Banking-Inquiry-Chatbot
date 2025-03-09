# 🏦 Bank Inquiry Chatbot using DistilBERT and T5

This project builds an AI-powered chatbot designed to handle user queries about general banking services. It uses **DistilBERT** for **intent recognition** and **T5** for **response generation**. The model was trained and tested on a dataset of **25,000 banking inquiries**.

---

## 📊 Project Overview

- **Objective:** Develop a chatbot that can accurately understand and respond to banking-related questions.  
- **Intent Recognition:** DistilBERT model trained to identify user intents from text input.  
- **Response Generation:** T5 model fine-tuned to generate relevant responses based on recognized intents.  
- **Validation:** Achieved **99.85% validation accuracy** for DistilBERT and **84% validation accuracy** for T5.  

---

## 📚 Dataset

- bitext/Bitext-retail-banking-llm-chatbot-training-dataset on hugging face
- **Size:** 25,000 rows of banking-related text inquiries.  
- **Structure:**  
  - **Input:** User questions (e.g., "How can I open a savings account?")  
  - **Output:** Predicted intent (e.g., "Account Opening") and generated response.  

---

## ⚙️ Technologies Used

- Python  
- TensorFlow  
- Transformers (DistilBERT, T5)  
- Google Colab 

