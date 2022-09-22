---
title: YouTube-dl on an Android phone
date: "2018-11-29T12:00:00.000Z"
template: "post"
draft: false
published: true
category: "Tech"
tags:
  - "Tech"
  - "Android"
  - "Python"
description: "Your Android Phone is Unix under the hood, so why not run a cli app on it where there is no actual mobile app for it yet?"
---

So one of the podcasts I listen to is the [Accidental Tech Podcast (ATP)](http://atp.fm) and one of the recurring topics around episode 300 has been an iOS app called iSH and the use of youtube-dl. iSH gives you access to a terminal shell on your iOS device and youtube-dl is a command line python app to download content from various online sources. I use youtube-dl quite a lot for various uses and honesty it’s become the go-to tool for some things now.

This got me thinking — I have an Android phone, why can’t I do this?

Well I can, and the instructions seem to be scattered across the internet so here is what I did from top to bottom.

(Heads up — I am using an Original Google Pixel 128GB on Android 9. Your mileage may vary on the below)

(Also, I’ll put all the commands at the bottom of this post so you can just “lift and shift” into Termux)

1. Download [Termux](https://termux.com/) from [Google Play](https://play.google.com/store/apps/details?id=com.termux)

1. Open Termux and run the following:termux-setup-storage This will allow Termux to access / write to the Android filesystem outside its own contrainer

1. Then run pkg upgrade which will allow Termux to update it's internal packages (think like apt-get)

1. Once complete, install python by running pkg install python. This will install Python (the language YouTube-dl is developed in) and also pip, the python dependency manager

1. Once python is installed, time to install YouTube-dl (finally). Run pip install youtube-dl and wait some time.

1. Lastly (optional possibly) I installed ffmpeg as I usually install it when I install YouTube-dl (this is as on some streams it will use ffmpeg to merge separate audio and video streams together). pkg install ffmpeg

1. Thats you

So to test it out you can now change the directory to the Downloads directory (cd ~storage/downloads) and attempt to download a video (youtube-dl https://youtu.be/BaW_jenozKc). If all works, you will see a freshly downloaded video file in your Downloads folder.

At the moment I have not worked out a use for this yet, but it’s nice to know I can use it in a pinch if I need to (such as when traveling and WiFi in your accommodation is hard to come by)

### Raw commands

This will take you through to having a video downloaded to your Downloads folder. For use in Termux


```shell
termux-setup-storage
pkg upgrade
pkg install python
pip install youtube-dl
pkg install ffmpeg
cd ~storage/downloads
youtube-dl https://youtu.be/BaW_jenozKc
```