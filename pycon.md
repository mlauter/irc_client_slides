# Make your own Smart AC

## Category
Other

## Duration
30 min

## Description
<!-- ( /400 chars) -->

## Audience
<!-- no idea what to put here -->
Home-automation enthusiasts 

## Python level
novice

## Objectives
To learn how to use python and a raspberry pi to control household devices over the internet.

## Abstract

## Outline

## Outline

### Part I, setup and Hardware
| Duration | Content |
| -------- | ------- |
| 1 mins | opening remarks
| 2 mins | parts, tools, resources 
| 1 min | addendum to tools: debugging hardware
| 1 min | brief mention of resources for setting up/configuring Pi
| total: | 5 min

### Part II, Simple Flask Server 
| Duration | Content |
| -------- | ------- |
| 1 min | walk through schematic of the whole project (UI--Server(+Datbase)--Pi--AC)
| 1 min | directory structure for a flask app
| 1 min | the world's simplest sqlite database
| 1 min | intro route decorators
| 2.5 min | main route 1: GET and POST from the UI
| 1 min | representing the state of the AC 
| 2.5 min | main route 2: POST from AC
| total: | 10 min

### Part III, 'Hey server! Hey server!': the program on the pi
| Duration | Content |
| -------- | ------- |
| 30 sec | edit pi files on your local text editor via ssh (rather than with nano)!
| 1 min | GPIO library for controlling i/o pins 
| 1 min | temperature sensor library and associated functions
| 1.5 min | requests library and making post requests
| 1 min | translating state instructions from server into action
| 1 min | maintaining a temperature range (thermostat style)
| 1 min | main loop, surviving server errors
| total: | 7 min

### Part IV brief demo
| Duration | Content |
| -------- | ------- |
| 2 min | video of the app in action
| total: | 2 min |

#### Total length: 25 mins

### Questions
5 mins

## Additional Notes
I've spent the past couple months at Hacker School, a 'writers retreat for programmers,' and I've given several lightening talks to the group of around 80 people (current students, facilitators, and alumni). I do not currently have a recording, but I will record the next talk I give and upload the video. I also presented a poster at the 2014 CUNY sentence processing conference. 

## Additional Requirements
Audio out


