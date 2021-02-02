# KUSH-GALAXY-6.66
First 2D game in Pygame. 

Inspired by a Youtube tutorial by @TechWithTim
Most assets were included by Tim on GitHub, all props to him ! 

The cause of this project was to get more understanding in how pygame and its syntax mainly works.
I deleted the included main.py from the tutorial and wrote line by line with the video.

Needed to retry a lot, got A LOT of statisfaction after fixing bugs and syntax/indent error after error.

This took me about 15hours spread over 2 days.

I might come back to this game and add more functionabiliies.
I'm allready amazed that this thing worked out.
One of the biggest challenges was importing my own background track in this game (was not included in the tutorial).
Had to play around with converting the mp3 file to wav/OGG, and had to play around with (os.path.join('', '' ))
to direct to the assets folder. sometimes this didn't work, instead i used ("Assets/filename.ext") and BOOM it worked.
The os.path.join was perfect for directing the images, ("Assets/Trackname.wav") was the solution for the audio track.
True another tutorial (mfw after 100 useless ones) i found : 

music = pygame.mixer.music.load('Assets/track.wav')
pygame.mixer.music.play(-1)

So i've learned in pygame the normal mixer doesn't plays several tracks at a time.
So you have to learn the mixer what song to loop, and others in the main function to play when triggered.

Took me a while, but now i know. 

TLDR ; im newb, basic functions still confuse me, music.load goes brrrrr, knowing syntax could have helped here. 


KUSH GALAXY 6.66 INSTRUCTIONS :

Welcome to KUSH GALAXY, the amazing basic bitch of a 2D galaxy shooter adventure !!! 

This is a 2 Player game, controlled on the same keyboard. 
All players have 10 health, first to reach 0 sucks rectum (according to what the game says guys, i'm sorry ...)
Max bullets = 3, reload after previous bullets made impact/dissapeared from the screen.

Background image & Background track by  Beacoupdargent, track title : Orbital 
Made in Ableton live 9 Suite.
Made this myself so there is no copyright infrigement ;). 

Yellow player on the left (YELLOW_SPACESHIP): 

            Controls:
  Shoot :             Ctrl (left)
  Move Up :           z
  Move Down :         a
  Move Left :         q
  Move Right :        d
  
  

Red player on the right (RED_SPACESHIP)

           Controls:
  Shoot :             Ctrl (right) 
  Move Up :           ARROW UP
  Move Down :         ARROW DWN
  Move Left :         LEFT ARROW
  Move Right :        RIGHT ARROW

  Thanks for playing and thanks for your time !
  
  -Dennis (Beaucoupdargent) 
  Antwerp    02/02/2021
