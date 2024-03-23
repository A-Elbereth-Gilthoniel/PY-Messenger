# R-Messenger

## Project Description:
 This project is a messaging application. Although it may not have as many features as WhatsApp or Telegram, it still provides users with the ability to communicate from a distance. The main distinguishing feature of our messenger compared to other similar applications is the existence of a single chat room for all users. Additionally, it is possible to create private chats.


 ## Implementation
  Our messenger is built on top of a server written in the **Flask** microframework, which is hosted publicly using the Heroku platform. Technological Requirements: Please refer to the **requirements.txt** file for more information about the technologies used in this project.

## Program start

Before beginning the program, please download `PyQt5`, `Flask` and `requests`

```Python
>>> pip install PyQt5
>>> pip install Flask
>>> pip install requests
```

Then run the file **flask-server.py**.

Thus, a message storage server is created.

Then, use the **Heroku** service to turn the local address 'http://127.0.0.1:8080/' into a global one.

In the file **main.py**, update the contents of the variable `L` with the local address with the newly created global address.

Then run the file **main.py**.

## Interface

Interface is made thanks to library `PyQt5`

+ The start page

![au] (https://github.com/A-Elbereth-Gilthoniel/images/blob/main/messenger1.png)

+ Authorization

![AA] (https://github.com/A-Elbereth-Gilthoniel/images/blob/main/messenger3.png)

+ Registration

![bb] (https://github.com/A-Elbereth-Gilthoniel/images/blob/main/messenger2.png)

+ Chat

![chat] (https://github.com/A-Elbereth-Gilthoniel/images/blob/main/messenger4.png)
