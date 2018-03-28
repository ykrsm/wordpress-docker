# Instruction to create local wordpress development enviroment usign Docker

# Prerequisite
To have the best output please try your best to prepare as close as possible enviroment as I used this make this happen.
Last time I test it is 2018/3/27

* macOS Sierra (Version 10.12.6)
* Docker version 17.12.0-ce
* docker-compose version 1.18.0
* WordPress version 4.9.4


# Step 1 Backup your production site.
I used WPEngine to host my wordpress site, and they have easy way to back up your production site.
![alt text](https://github.com/YukiKuroshima/wordpress-docker/blob/master/doc/Screen%20Shot%202018-03-27%20at%209.40.28%20PM.png)
Click "Back up now" and you will get confirmation email.

# Step 2 Get your content
Go to the back up page in wp engine.

Select your back up point. Your docker container is going to use this content.
![alt text](https://github.com/YukiKuroshima/wordpress-docker/blob/master/doc/Screen%20Shot%202018-03-27%20at%209.40.28%20PM.png)

Click "Download ZIP" and select "Full backup"
![alt text](https://github.com/YukiKuroshima/wordpress-docker/blob/master/doc/Screen%20Shot%202018-03-27%20at%2010.13.12%20PM.png)
You will get the download link to the email you typed in couple of minutes.
Download that and keep it where you can find easily. You will need it in the next step.

# Step 1 Get database dump
# Step 1 Prepare your wordpress container# wordpress-docker
