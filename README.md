
# COVID-19 Chatbot using RASA 🤖

A conversational AI chatbot built with RASA to answer COVID-19 related queries.
This chatbot uses Rasa NLU for intent classification, Rasa Core for dialogue management, and is integrated with Telegram for real-time conversations.



## 📌Features
-Answers FAQs related to COVID-19\
-Handles greetings, goodbyes, and bot challenges\
-Provides information on virus spread, risks, and myths\
-Works with Telegram integration\
-Extensible with new intents and stories

## 🛠️ Tech Stack
-Python 3.x\
-RASA (Rasa Open Source & Rasa X)\
-Spacy (for NLP pipeline)\
-Ngrok (for webhook tunneling)\
-Telegram Bot API

## 🚀 Installation & Setup
### 1. Clone the Repository

```bash
git clone https://github.com/your-username/covid19-chatbot-rasa.git
cd covid19-chatbot-rasa

```
### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


```
### 3. Install Dependencies
```bash
pip install rasa
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
pip install spacy
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en

```
### 4. Initialize RASA Project
```bash
rasa init
```
### 5. Train the Model
```bash
rasa train

```
### 6. Run the Chatbot (Local)
```bash
rasa shell
```

    
## 📂 Project Structure
covid19-chatbot-rasa/\
│── data/             # Training data (intents, stories)\
│── models/           # Trained models\
│── actions/          # Custom actions (if any)\
│── domain.yml        # Bot responses & actions\
│── config.yml        # Pipeline and policies\
│── credentials.yml   # Telegram / other integrations\
│── endpoints.yml     # Action server details\

## 📸 Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 📖 References

 - [Rasa Documentation](https://rasa.com/docs/)
 - [Telegram Bot API](https://core.telegram.org/bots/api)



## ✨ Future Enhancements
-Add multilingual support\
-Voice-based chatbot integration\
-Deployment on cloud (AWS / Azure / GCP)\
-Advanced analytics & monitoring
