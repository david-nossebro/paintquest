# PaintQuest

Some slides: <br />
https://docs.google.com/presentation/d/1DAzAl6hBoVgYhI9QsRxjKcFxVN4sxI7pWDr_bfjmU-s/pub?start=false&loop=false&delayms=10000

##Why?
* To have fun
* To learn
* To socialize and collaborate
* To succeed

##How?
By having fun, sharing our knowledge and laugh toghether we are going to solve complex problems and extend our common wisdom. Passion, knowledge and consistency will make us succeed.

_"One small idea may grow big if you share it with friends."_

##What?
The idea of PaintQuest (which by the way is just a working title and may be changed) is a browser based shared canvas which can grow and be infinitely large. This means that all users connected will work on the same canvas in realtime. Think of it like a paint equivalent to Minecraft. Another similar application (but for text) is "Your world of text" which can be found here: https://www.yourworldoftext.com/.

_"Art is about expressions, whether it´s a painting, a poem or a piece of code. Express yourself and be an artist."_

##Environment
You will find a list of all the frameworks further down this page. If you want to setup your own environment, those links contain good "getting started guides". To make it easy for you to get started we made a preinstalled VMware image, just download it and you´ll have everything you need to get started.

###Vmware image<br />
https://github.com/PaintQuest/paintquest/raw/master/docs/env/paintquestenv7z.torrent (3,2gb)<br />
https://github.com/PaintQuest/paintquest/raw/master/docs/env/paintquestenv.torrent (4,2gb)<br />
Password: paint <br /><br />

Inside the virtual machine you´ll find this git repository checked out in "/home/paint/paintrequest", start by open a terminal and go there and bring in the latest code with the following command:
```
cd /home/paint/paintquest/ && git pull
```

To bring up a small laboration you can enter the following command:
```
chromium-browser /home/paint/paintquest/src/mspaint/index.html & 
chromium-browser /home/paint/paintquest/src/mspaint/index.html & 
deepstream start
```
This will open a chromium browser with two tabs with a canvas in each.

Visual studio code is installed if you want to start laborating. For getting started guides and docs you´ll find links to the different frameworks below. Most basic stuff is preinstalled.

###Google drive
https://drive.google.com/drive/folders/0BzMKFQAMC0S2T0cweU1ncEFZODA?usp=sharing <br />
A shared folder.

###Slack
https://paintquest.slack.com <br />
This is where we hang out in sickness and health. Remember that no idea is too small and no problem too big. Come and be a part of the great team! 

###Spotify playlist
https://open.spotify.com/user/snuggles88/playlist/2ud2VzegSwJEHBFYXlh6u7 <br />
Since this is an open source project and we´re sharing everything, we can as well share our taste in music too. Feel free to add your songs! :)

##Frameworks
Suggestions of frameworks for this project are:

https://www.rethinkdb.com/ <br />
The open-source database for the realtime web.

https://deepstream.io/ <br />
the open realtime server <br />
a fast, secure and scalable websocket & tcp server for mobile, web & iot.

http://vuejs.org/ <br />
The Progressive JavaScript Framework.

http://www.pixijs.com/ <br />
Create beautiful digital content with the fastest, most flexible 2D WebGL renderer.
