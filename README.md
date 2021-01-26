# HolidayRoom
Hardware Project
## Inspiration
What a terrible year was 2020. You might not have seen your friends nor visit your relatives. Can you imagine the winter holidays without friends and relatives? You might be sad like we are. Therefore we thought to make something crazy, to lessen our boredom and feel more homely. We bring you our project holiday room.

## What it does
Holiday Room is a Robot Santa trapped inside your room, programmed to destroy your boredom. It is our website; it contains information about our hardware project, including components used and features of our hardware and our team.

## How we built it
The bot connects to a Bluetooth speaker cum mic. It listens through the mic constantly. Converts speech to text using a python script and searches keywords in it to execute commands. When it finds any set of commands, it executes the according to the subroutine and displays the command, which was executed on LCD via I2c; the IO extender bridges the requirements of lots of gpio pins wiring and reduces the Hassel for controlling LCD. When the bot greets back, it uses a text to speech synthesizer to playback what it wants to say. When the bot plays music, it loads one of many music files stored in its directory. The audio is broadcasted over Bluetooth so the speaker can play it. -> If you wish it Merry Christmas, it will reply you back and, it will show merry Christmas on the LCD screen. -> If you ask it to play a song, it will choose one of the songs randomly from the Christmas files and play one of them. -> You can even pause songs, stop songs, and resume the songs. -> If you ask it to show a Christmas tree, it will show you a Christmas tree on the LCD screen.

## Components used in our hardware
Raspberry Pi 3b+:- It does listen to a Bluetooth mic. Does speech to text conversion, Looks for keywords to perform actions like play a random Christmas carol, pause, resume, and stop the music. It also kind enough to wish back when you wish the bot merry Christmas. It plays the music and greets over a Bluetooth speaker.

16x2 LCD:- LCDs the command the bot last executed.

I2c IO expander for LCD:- And the io extender makes it easy to connect pi with the LCD.

## Challenges we ran into
It was our first time using an LCD and text to speech converter in our project, so we did run into some challenges to make these work.

## Accomplishments that we're proud of
We are extremely proud of our team as we could incorporate everything that we wished for in our project, even in this short duration.

## What we learned
We learned a lot about hardware in this hackathon.

## What's next for Holiday Room
We are planning to make the hardware tool more user friendly and beautiful to look at.

## Built With
css3
extender
html5
javascript
lcd
python
raspberry-pi
## Try it out
 holidayroom.study
 GitHub Repo
