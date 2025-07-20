🤖 MAC – The Helper
MAC – The Helper is a multifunctional desktop assistant built using Python that combines speech recognition, GUI interaction, WhatsApp messaging automation, and social media integration. Designed as a user-friendly assistant, MAC aims to simplify everyday digital interactions through voice commands and visual interface support.

💡 Key Features
🎙 Voice-Enabled Chatbot
MAC is equipped with a speech recognition module that allows users to interact with the assistant via voice. Using Google's Speech Recognition API and gTTS (Google Text-to-Speech), MAC can both understand spoken words and respond vocally. Whether you're asking for a joke, basic facts, or just having a casual conversation, MAC provides instant replies with a human-like feel.

💬 Intelligent Response System
The chatbot uses NLTK (Natural Language Toolkit) for text tokenization and preprocessing. It identifies user intent and gives appropriate responses, whether it's a greeting, farewell, or general question. The system is simple yet effective for casual AI-based interactions.

💬 WhatsApp Automation
Powered by PyWhatKit, MAC can schedule and send WhatsApp messages directly from the interface. Users only need to enter a phone number, message, and scheduled time. This feature is especially useful for automating reminders, birthday wishes, or business notifications.

📸 Instagram Integration
MAC includes Selenium-based Instagram automation, allowing users to log in, visit user profiles, and follow them. The GUI provides fields for login credentials and username input to interact with Instagram accounts seamlessly.

🖼 GUI with Tkinter
MAC runs on a visually appealing interface built using Tkinter and ttk widgets. It supports multiple tabs, including:

Chatbot tab for user interaction

Instagram tab for social automation

WhatsApp tab for messaging automation

All images, icons, and layouts are managed for an aesthetic and interactive user experience.

🛠 Technologies Used
Python 3

Tkinter (GUI development)

PyWhatKit (WhatsApp integration)

Selenium WebDriver (Instagram automation)

SpeechRecognition (Voice input)

gTTS (Google Text-to-Speech) (Audio response)

NLTK (Text processing)

Pillow (Image handling)

⚙ How It Works
Run the application to launch the GUI.

Use the Chatbot tab to either type or speak your queries.

Switch to the Instagram tab to log in and interact with user profiles.

Schedule a WhatsApp message via the WhatsApp tab by entering number, message, and time.

Get voice responses from the assistant for a more interactive experience.

📌 Use Cases
Casual AI chatting and voice interactions

Automated WhatsApp reminders/messages

Social media engagement via Instagram

A starting point for building advanced personal assistants

🚀 Future Improvements
Integration with more social platforms (e.g., Facebook, Twitter)

Real-time weather/news using APIs

Better natural language understanding using transformer-based models

Calendar and email automation

🙌 Author
Developed by Sambhav Jain
Project: MAC – The Helper
Technologies: Python, AI/ML, Automation, GUI
Open to feedback and collaboration.
