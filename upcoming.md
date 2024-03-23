---
layout: default
title: "Upcoming"
permalink: /upcoming/
---

<h1>Work In Progress Projects</h1>

<h2><u>AI Speech API Tool</u></h2>
This goal of this project is to create a chat bot that you have to talk to using your mic, and I want to do it using only free apis, as I've seen another project like this before but it was using 3 different paid apis. Currently what I have done for the project is create a speech-to-text function in order to be able to send the message to whatever chat bot API I end up using. My end goal for the project is to have the bot talk back using somesort of text-to-speech in order for the conversation to feel just a little bit natural.<br><br>
<h3>Update #1</h3>
In the current state of the project, you can talk to the HuggingChat AI using your only your mic, and it will respond back to you in text-to-speech using gTTs. This was the original goal of the project, but now after creating it I have had new ideas that I want to try and implement. There are two specific ones I want to try which is to speed up the text-to-speech as it is quite slow, and I want to give the chat bot a starting prompt without having to print it's response, which has been a little bit harder than I thought to do.
<br>
<br>
<h3>Update #2</h3>
The project has been uploaded to github which you can check out <u><a href="https://github.com/janGithub122/AudioChatbot" target="_blank">here</a></u>. Currently I've added a way to configure the TTS' speed, but I'm yet to add a pitch configuration, so hopefully I can get that done soon.<br><br>

<h2><u>RGBdle</u></h2>
In my past projects, they've all been just scripts that the user has to run inside of a command line, so in this project I want to create something that's visual. What I want to do with this project is create a Worlde-like web application with flask. Instead of having the user guess words, I want the user to attempt to guess a given color's RGB values. I currently have a bit of progress, and the main focus right now is functionality over visuals, as I should just be able to paint over the bare bones<br><br>
<h3>Update #1</h3>
So far the current build of the website can take in user submitted values and save them, but it's been pretty hard to figure out how to take the users value and check if it equals the random RGB value. It took a while to figure out how to get a users form data without refreshing the page since it required JavaScript, so now I'm not sure whether or not I need to write more JavaScript. What also doesn't help is that most of the attempts to check the users guess seems to always result in some other part of the code breaking.<br><br>
<h3>Update #2</h3>
I've managed to fix the reload problem from the last update, which did end up requiring me to include a little bit of JavaScript. After fixing that, I then managed to have the python script correctly check the users guess to see if it matches the randomly generated RGB values, though it only tells me through the python terminal. With the update #1 problems out of the way, my next step will be to have the website show the user if their guess is right or wrong, and then show hints if their guess was wrong.

