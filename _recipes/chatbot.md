---
title: "Kscout Virtual Assistant"
image: 
  path: /assets/images/chatbot.jpg
  thumbnail: /assets/images/chatbot.jpg

---
Chatbots have changed how a service provider gives services to their consumers. Chatbots are effective for introducing your platform to new users.

I contributed in the development of Scout Virtual assistant. It is a chatbot for kscout.io platform. Kscout.io is an opensource project, which act as a markettplace for Knative apps where users can search and deploy serverless apps.

## Description 

1. Scout helps users to search apps on the platform, deploy them to clusters and also helps users with any queries regarding serverless.
2. The implemented chatbot api is robust and can be easily integrated with any messaging platform abd IDEs
3. Currently the chatbot is integrated with the kscout.io websitte, slack and VSCode IDE extension.
4. The api makes use of IBM`s watson api to create conversations. It uses natural language understanding, and integrated dialog tools to create conversation flows between the platform and users.
5. The chatbot api source code can be found at [Chatbot Api](http://github.com/kscout/chat-bot-api) 
6. Source code for slack and ide integrations are : [Slack client](https://github.com/kscout/slack-chat-bot-api) , [VSCode Exttension](https://github.com/kscout/kscout-ide-extension)

## Technologies Used

* VScode Extension API
* IBM Watson Assistant API
* NLTK
* Slack Events api
* sklearn
* Python
