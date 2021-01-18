---
layout: post
title: A bot that pawrfectly returns cute cat images if you tail it to!!! 
categories:
- Tech
feature_image: "https://1000logos.net/wp-content/uploads/2018/01/WhatsApp-Logo.png"
---

So what is this bot and how does it work. It simply is a normal WhatsApp bot which takes in input(a specific keyword) from the message we will send it and it will return the desired output. It was made as an attempt to understand how api's work, how web apps work in general and how to deploy our web apps to Heroku platform. 

Technologies used - Heroku to host the app, Twilio api which provides with the communication services where we can host our bot, Third party api's which will provide us with data to return to the user, Flask for python based web frame working, ngrock for testing with a public URL.

### Steps to use the bot :-

* Open your WhatsApp, now save this phone number **+1 415 523-8886**  with the name **Bot** 

* Now refresh your contacts and search for **Bot**  now type in the message **join zero-physical** and send it

  <img src="https://user-images.githubusercontent.com/26514224/104945372-7d188b80-596d-11eb-91bd-e9dcf6095ea0.jpeg" alt="WhatsApp Image 2021-01-18 at 8.30.58 AM" style="zoom:50%;" />

* Now you are connected to the bot.

*  Just say **Hi** and you will get all the functionalities of the bot.

  ​                                            <img src="https://user-images.githubusercontent.com/26514224/104945404-8d306b00-596d-11eb-9378-058fff8b00f9.jpeg" alt="WhatsApp Image 2021-01-18 at 8.31.22 AM" style="zoom:50%;" />

Examples :-

​                             <img src="https://user-images.githubusercontent.com/26514224/104945462-a1746800-596d-11eb-8879-7194107be97d.jpeg" alt="WhatsApp Image 2021-01-18 at 8.31.49 AM" style="zoom:60%;" />

​                            

​                             <img src="https://user-images.githubusercontent.com/26514224/104945511-b3eea180-596d-11eb-8f39-b69ca67549e4.jpeg" alt="WhatsApp Image 2021-01-18 at 8.32.02 AM" style="zoom:60%;" />

​                            

​                            <img src="https://user-images.githubusercontent.com/26514224/104945552-c49f1780-596d-11eb-873c-0d0631017f52.jpeg" alt="WhatsApp Image 2021-01-18 at 8.32.12 AM" style="zoom:60%;" />



So yes this is the bot, I won't get into technical details but basically. When we are sending a request for a "quote" it is going to Twilio and to give an response Twilio will use a webhook were the logic for processing that request is stored which in this case happen to be a Heroku web app. From there the program will run and provide Twilio a response to the message which it will show as an reply to us.

#### Acknowledgement:-

https://www.twilio.com/docs/whatsapp/api

https://www.twilio.com/blog/build-a-whatsapp-chatbot-with-python-flask-and-twilio

https://levelup.gitconnected.com/how-to-create-covid-whatsapp-bot-2d424c96a4d6



