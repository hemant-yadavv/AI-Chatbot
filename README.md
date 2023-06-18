# AI Chatbot using Django and GPT-3.5-turbo API
This project is an AI-powered chatbot developed using Django, a popular Python web framework, and the GPT-3.5-turbo API provided by OpenAI. The chatbot leverages the powerful natural language processing capabilities of GPT-3.5-turbo to generate human-like responses and engage in interactive conversations with users.

# Prerequisites
Before running this project, ensure that you have the following dependencies installed:

* Python 3.7 or higher
* Django 3.2 or higher
* OpenAI Python library (openai) 0.27.0 or higher
 
You will also need an API key for the GPT-3.5-turbo API. If you don't have one, you can sign up at the OpenAI website and obtain an API key.

# Installation

1. Clone the project repository:

        git clone https://github.com/hemant-yadavv/AI-Chatbot.git

2. Change into the project directory:

        cd django_chatbot

3. Open the chatbot/views.py file and replace OPENAI_API_KEY with your actual GPT-3.5-turbo API key.

# Usage

1. Start the Django development server:

        python manage.py runserver
2. Open your web browser and visit 'http://localhost:8000' to access the chatbot interface.
 
3. Enter your message in the chat input and press Enter. The chatbot will process the input using GPT-3.5-turbo and display the generated response on the screen.

4. Continue the conversation by entering more messages and observing the chatbot's responses.

# Customization
You can customize the chatbot's behavior and appearance by modifying the Django project files. Here are some areas you might consider customizing:

* Templates: The HTML templates used for rendering the chatbot interface are located in the templates directory. You can modify these templates to change the layout, styling, or add additional features.
* Models: The chatbot/models.py file defines the data models used by the chatbot. You can modify these models to store and retrieve additional information as needed.
* Conversation handling: The conversation logic is implemented in the chatbot/views.py file. You can customize how messages are processed, how the chatbot interacts with the GPT-3.5-turbo API, and how responses are displayed.

# Disclaimer
This chatbot relies on the GPT-3.5-turbo API for generating responses. It's important to note that the behavior of the chatbot is determined by the training data used by OpenAI and the instructions provided during the conversation. Although the chatbot strives to provide accurate and helpful information, it may occasionally produce incorrect or inappropriate responses. It's advisable to review and moderate the chatbot's output before using it in a production environment.

# I hope this helps!                                          
