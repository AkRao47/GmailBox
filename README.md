<p align="center">
    <a href="https://github.com/H7AM0/GmailBox">
        <img src="https://telegra.ph/file/19f7cbbf3959941cda6b5.jpg" alt="Hamo" width="128">
    </a>
    <br>
    <b>create random Gmail and receive messages</b>
    <br>
    <a href="https://www.instagram.com/4.4cq/">
        instagram
    </a>
    •
    <a href="https://t.me/pyrogram">
        News
    </a>
</p>

# GmailBox

> With this library, you can create random Gmail and receive messages

``` python
from GmailBox import GmailBox

Gmail = GmailBox()
```
## Generate a random Gmail
``` python
New_Gmail = Gmail.newEmail()
print(New_Gmail)
```
## to get the inbox
``` python
email = New_Gmail['email']
inbox = Gmail.inbox(email)
print(inbox)
```
### Installing

``` bash
pip3 install GmailBox
```
