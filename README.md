<div align="center">
 
# Whatsapp Bot 

</div>

## Features

| Sticker Creator |                Feature           |
| :-----------: | :--------------------------------: |
|       ✅       | Send Photo with Caption          |
|       ✅       | Reply A Photo                    |
|       ✅       | Image Url                        |
|       ✅       | Animated sticker using giphy url |


| Downloader |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |   Tiktok Downloader (No WM & WM)              |
|       ✅        |   Twitter Video Downloader                    |
|       ✅        |   Facebook Video Downloader (SD & HD)         |
|       ✅      |   Instagram Video Downloader                  |


| Other  |                     Feature                     |
| :------------: | :---------------------------------------------: |
|       ✅        |   get a meme from random subreddit            |
|      BETA        |   OCR > get text from image            |


| Grup Only  |                     Feature                     |
| :------------: | :---------------------------------------------: |
|       ✅        |   Promote User                  |
|       ✅        |   Demote User                   |
|       ✅        |   Kick User                     |
|       👷       |   Mention All User      |

## To-Do
 - More Refactoring
 
---

## Getting Started

This project require NodeJS v12.

### Install
Clone this project

```bash
> git clone https://github.com/YogaSakti/imageToSticker.git
> cd imageToSticker
```

Install the dependencies:

```bash
> npm install
```

### Usage
1. run the Whatsapp bot

```bash
> npm start
```

after running it you need to scan the qr

### Troubleshooting
Make sure all the necessary dependencies are installed: https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md

Linux & C9 Fix: https://trakteer.id/red-emperor/showcase/fix-whatsapp-bot-sticker-creator-di-c9-lpwel

### Run it on heroku
Just push it on heroku. We've already added Procfile and necessary buildpack for bot run properly.

### Run it on Google Cloud VM Instance
First of all. You need to install git and node in your VM machine, and also ```sudo apt-get update```, don't forget it. 😒

**Clone this repository**
```
git clone https://github.com/J3ndra/imageToSticker
cd imageToSticker
```
Then, install using ```npm install```

**Install it into your machine**
```
sudo apt-get install -y libappindicator1 fonts-liberation libasound2 libgconf-2-4 libnspr4 libxss1 libnss3 xdg-utils
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome*.deb
```
If you get broken installation ```sudo apt --fix-broken install```

And if it still can not run in VM Instance, try ```/usr/bin/google-chrome-stable --headless --disable-gpu --dump-dom "https://sepehr.irib.ir/?idc=32&idt=tv&idv=1"``` then **ctrl^z** or **cmd^z**

### The main code belongs to [YogaSakti](https://github.com/YogaSakti/imageToSticker)
