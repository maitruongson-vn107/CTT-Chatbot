# CTT-Chatbot
CTT Chatbot source code
* Introduction
  - Rasa source code for CTT Chatbot FB application, using FB Messenger as UI/UX.
  - CTT Chatbot is an AI chatbot providing HUST students with neccessary and personal informations (schedulers, notifications,...).
  - CTT Chatbot, developed by a 5-student group from HUST, won First Prize at SoICT-IBM Hackathon 2020 (host by SoICT, HUST in June 2020).
* Descriptions of files
  - --init--.py: empty file that helps python find actions
  - actions.py: code for actions
  - config.yml: configuration for NLU and Core model
  - credentials.yml: details for connecting to other services
  - data/nlu.md: training data (intents...)
  - data/stories.md: stories - dialog configurations
  - domain.yml: assistant's domain
  - endpoints.yml: details for connection to FB messenger
  - environment.yml: informations of env variables
