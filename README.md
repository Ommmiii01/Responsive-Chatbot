# Chatbot with Flask and DialoGPT

This repository contains a Flask-based chatbot web application integrated with Hugging Face's **DialoGPT-medium** model for natural language conversation. The chatbot processes user inputs and generates responses using a transformer-based model, providing an interactive web interface with Bootstrap. 

Key Features:
- Uses DialoGPT-medium for conversational AI.
- Built with Flask for web integration.
- Dynamic and responsive UI built with Bootstrap.
- Communicates via AJAX for real-time chat updates.

# Requirements
Before running the project, you need to install the following libraries:

# Python Libraries
Flask: Web framework to build the chatbot interface.
transformers: Hugging Face's library to use pre-trained language models like DialoGPT.
torch: PyTorch, required to run the model.

# Other Requirements
Bootstrap: For the UI (linked via CDN in chat.html).
jQuery: For real-time AJAX communication (also linked via CDN in chat.html).
