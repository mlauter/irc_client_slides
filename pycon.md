# Make your own Smart AC

## Category
Other

## Duration
30 min

## Description
<!-- ( 318/400 chars) -->
Looking for a fun, useful Raspberry Pi project? Want to connect your household appliances to the internet? Come learn how to build your own 'smart' air conditioner using a Raspberry Pi, a bit of hardware, and, of course, Python. Plus, you can save energy and never have to come home to a sweltering bedroom again. 

## Audience
<!-- no idea what to put here -->
Anyone who still doesn't know what to do with their Raspberry Pi

## Python level
novice

## Objectives
Learn everything you need to know to go home and set up your own Smart AC; and what's more, become familiar enough with these tools and Python libraries to create your own awesome home-automation projects. 

## Abstract

What with the proliferation of device/applications for remotely controlling everything from your lights to your coffee maker, and with the release of HomeKit in iOS 8, it's clear that companies big and small are getting into the home-automation game. But why just not do it yourself?

In this talk, I'll show you everything you need to know to turn your boring window-unit air conditioner into a wifi-enabled, remotely controllable smart-thermostat. With a couple components, a Raspberry Pi, and some handy Python libraries, you'll not only have the tools to make yourself a Smart AC, you'll be able to execute other cool home-automation projects you've dreamed up. (I'm thinking an alarm for the morning that starts my coffee pot.)

You do not need to have any previous experience with Raspberry Pi or hardware projects. I'll go over the simple circuits you'll make, tips for debugging hardware, the libraries you'll need, and how to set up a simple flask server that will allow you to communiate with your device from your web browser. I'll wrap up the talk with pointers to some excellent resources and a quick video demo of my Smart AC in action.

## Outline

### Part I: Setup and Hardware, 5 mins
* Overview of the project 
* What you'll need
* Where to find good tutorials
* Two very simple circuits
* quick notes on debugging hardware

### Part II: Simple Flask server, 10 mins
* A simple sqlite database
* Intro to routes
* Constructing the routes for UI and Pi
* Representing the state of the AC

### Part III:  The program on the Pi, 8 mins
* Important libraries (especially RPi.GPIO, Requests)
* Making POST requests
* Temperature control (how to write a thermostat)
* Surviving server non-responsiveness

### Part IV: Demo, 2 mins
* a video of my version of this project in action

### Questions, 5 mins

#### Total 25 mins + 5 for questions

## Additional Notes
### On this project
This is a project I have already completed. I actively use it in my room (or I did in the summer anyway). Not only that, I've also already thought a lot about how to make it accessible to others, regardless of their experience level with hardware/Raspberry Pi. Here is a link to [my writeup](https://mlauter.github.io/how-to-make-your-own-smart-ac/) about it on my blog. I'm also working on a submission to [Instructables.com](http://www.instructables.com/)'s ['teach it'](http://www.instructables.com/contest/teachit/) contest, and I'll upload that link once it's on the site. Finally [here's a link](https://www.icloud.com/photostream/#A95oqs3qcUCpO) to a video demo I made of the simple on/off mode of my own Smart AC. 

### On speaking experience

I've spent the past couple months at [Hacker School](https://www.hackerschool.com/), a 'writers retreat for programmers,' and I've given several lightening talks to the group of around 80 people (current students, facilitators, and alumni). I do not currently have a recording, but I will record the next talk I give and upload the video. I also presented a poster at the [2014 CUNY](https://cuny14.osu.edu/program) sentence processing conference. 

## Additional Requirements
Audio out


