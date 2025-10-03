# -Powered-Conversational-ChatBot-Web-App
This project is a web-based chatbot using the Microsoft DialoGPT-medium model with a Flask backend and a simple HTML/CSS/JS frontend. Users can interact with the bot through a web interface styled with Bootstrap and FontAwesome. The backend handles natural language processing using HuggingFace’s transformers library.

# ChatBot

A conversational web chatbot built with Flask (Python), HuggingFace transformers (DialoGPT-medium), and a Bootstrap/JS frontend.

## Team Attribution
Project developed by:
- Gopika R 
- Guidance by: Prof.Karthikyean

## Features
- Engages users with conversational AI (DialoGPT-medium)
- Modern, responsive chat interface
- Real-time bot responses
- Easy setup for local deployment

## Folder Structure
- app.py          # Flask backend server
- chat.html       # Frontend chat interface
- requirements.txt# Project dependencies

## Installation & Setup

### 1. Install Python and pip
Check Python and pip versions:
https://www.dataquest.io/blog/installing-python-on-mac/

[Install pip]
https://phoenixnap.com/kb/install-pip-mac
If you have Python & pip installed then check their version in the terminal or command line tools
python3 --version
pip --version

Installing Flask
In your terminal run the requirements.txt file using this pip
pip install -r requirements.txt

Running ChatBot Application in Terminal
cd into your directory

What you will create
In this tutorial, I will guide you through the process of building a chatbot that can carry out conversations with users using natural language processing.

To start, we will be using Microsoft DialoGPT, a pre-trained language model that can generate human-like responses to given prompts. We will be integrating DialoGPT with Flask, a popular Python web framework, to create a web application that can communicate with users via a chat interface.

For the frontend of our application, we will be using HTML, CSS, and JavaScript to create a visually appealing and interactive chat interface. Additionally, we will be using jQuery to handle the HTTP requests that are made to the backend server.

Throughout the tutorial, I will provide step-by-step instructions on how to set up your development environment, install the necessary dependencies, and create the required files and code for the application. I will also explain how to train and fine-tune the DialoGPT model to improve the accuracy of its responses.

By the end of this tutorial, you will have a fully functional chatbot that can engage in conversations with users, and you will have gained valuable experience in using Microsoft DialoGPT, Flask, and web development technologies such as HTML, CSS, and JavaScript.

ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.
https://huggingface.co/microsoft/DialoGPT-medium

User-Html
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';

  Bot-HTML
  var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
  ![WhatsApp Image 2025-10-03 at 18 24 30_66d52c23](https://github.com/user-attachments/assets/9a849d12-cfb4-47f0-bea1-c297f9485b51)

  <img width="1402" height="749" alt="image" src="https://github.com/user-attachments/assets/d364f5f0-c470-4bb0-9a21-a8783da1e7f7" />

