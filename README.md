# Building-a-Support-Agent-Chatbot-for-CDP-How-to-Questions
# Project Overview
This project is a chatbot that helps users find answers to "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot extracts relevant information from the official documentation of these platforms and provides the user with step-by-step guidance.

# Features
Answer "How-to" Questions: The chatbot can respond to user queries about how to perform tasks in Segment, mParticle, Lytics, and Zeotap.
Extract Information from Documentation: The chatbot can navigate through the official documentation of each platform and extract relevant instructions.
Handle Variations in Questions: The chatbot handles variations in phrasing and terminology.
# Bonus Features:
Cross-CDP Comparison: The chatbot can compare functionalities between the platforms.
Advanced "How-to" Questions: The chatbot can answer more complex questions related to integrations and configurations.
# Data Sources
The following official documentation is used to retrieve information:

Segment Documentation: Segment Docs
mParticle Documentation: mParticle Docs
Lytics Documentation: Lytics Docs
Zeotap Documentation: Zeotap Docs
# Technologies Used
Python: Backend programming language.

Flask: Web framework to create the chatbot interface.

NLTK: Natural Language Processing for query analysis.

HTML/CSS/JavaScript: Frontend for creating the chatbot user interface.

# Installation Instructions
Clone this repository:

git clone https://github.com/yashaswinikm242003/chatbot_project.git
cd chatbot_project

Install the required dependencies: pip install -r requirements.txt
Run the Flask app: python app.py
