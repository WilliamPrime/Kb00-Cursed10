---
title: "The more cursed the more better"
author: "William Wallace"
description: "a really cursed keyboard with an extra cursed layout"
created_at: "2025-07-17"
---

Note: despite me putting created as the current date, i have been working on this for a month or so, i just put the date i actually started uploading this to github

so i started working on this RIGHT at the start of infil

# total time : 
(ive also not done it by date, but by day, and removing the gaps...)


# day 1-3    time: 2 hours

trying a few different layouts in keyboard layout editor.
my goals with this were to create a keyboard that met all the following:
- as compact as possible
-   avoid things i dont need like knobs etc
- a fullsize layout but compacted and with additional keys

here are some of the layouts that i started thinking about
  <img width="2171" height="783" alt="image" src="https://github.com/user-attachments/assets/33a36dce-54be-4fac-b97c-20198ead4d4a" />
  <img width="2290" height="750" alt="image" src="https://github.com/user-attachments/assets/86868c31-0c54-488f-ae5a-f550b6766150" />

but ultimately i decided on this layout because i liked the no gaps look and given that im trying to make my keyboard as compact as possible while not loosing keys, this seems like a reallyyy cursed but acceptable solution for that problem.

<img width="1382" height="446" alt="image" src="https://github.com/user-attachments/assets/a9cd4f0a-408e-449e-87e2-dadef758d4e6" />

 
# day 4 making a schematic on kicad    time: 1h 25min
<img width="1410" height="1134" alt="image" src="https://github.com/user-attachments/assets/90fd78d3-a27a-4ee1-917e-964f6a5579f8" />
this was a little tricky trying to make sure i double and tripple checked that i had all the switches i needed

# day 5 Starting to layout  the pcb    time: 2 hours
this day was truely painful, there is a reason there arent any pictures here

short version of this day is:
- focusing on the pcb
- REALLY FOCUSSING
- forgot to save
- windows black screen of deathed (its not even blue anymore, sad)
- lost this days progress 😭


# day 6 starting to layout the pcb part 2 ,  time: 1hour

after having done this task once allready the previous day it made it a lot faster this time as i had allready re learnt and remembered how to do stuff
(add images here)

so this one was a breeze
i also sort of work out what techniques i had to use to get all the correct spacing for the keyboard

# day 7-9 doing all the tracing and finishing the PCB  time: 3hours
there were a lot of traces
it turns a keyboard with a ton of keys has a ton of traces 
(add imgs here)




# day 10 - 14 the CAD  time: 6hours or so
the CAD was a bit of a struggle trying to get a way to mount the pcb while trying to minimise both the height of the keys, and any brims arround the edge of the board



so here is a final render of the full keyboard


but now for the "fun" of how we ended up here!
<img width="1765" height="904" alt="image" src="https://github.com/user-attachments/assets/156cba08-d299-461e-b17b-bf4f1a6402d6" />

i decided to add keycaps because i wanted to see what the thing looked like all together
<img width="2021" height="874" alt="image" src="https://github.com/user-attachments/assets/a8840b85-efe4-4fba-aa7a-9bcc8378b14e" />

next part was the plate because i knew i was going for plate mount and then sandwich that (i hope im using the right terms lol)
<img width="1748" height="666" alt="image" src="https://github.com/user-attachments/assets/0a7a6658-19da-422d-8fbc-6cb1f632eb04" />

then it was a case of fighting through the cad to try and balance the keyboard case border
and how easy it would be to get in the screws to hold it all together and make sure i can 3d print it in smaller parts 

<img width="1517" height="703" alt="image" src="https://github.com/user-attachments/assets/93cf676d-dc68-40cc-8fa2-e3317ff26fac" />
in splitting up the case i decided to stagger everything to try and hope to hold it together well

<img width="1995" height="376" alt="image" src="https://github.com/user-attachments/assets/8d4f4954-661a-4854-9c04-5de965aca436" />
<img width="1933" height="1041" alt="image" src="https://github.com/user-attachments/assets/d1289d3d-ac05-472c-a841-af783c3f7072" />

then it was time for the really big challenge i predicted earlier
trying to get the screws  to go where i wanted them to !
<img width="952" height="793" alt="image" src="https://github.com/user-attachments/assets/8727468d-c431-44c3-9efc-10a8c7e5ebd5" />





now its the point where it gets hard
because i really didnt want a massive bordere arround my part
but i knew i needed screw to hold it together
and i really didnt want to go back to the PCB to add the holes so i had to get a lil creative designing


<img width="512" height="739" alt="image" src="https://github.com/user-attachments/assets/30bedc20-5fcd-4543-a32c-91e8f1f346a2" />
this solution left 0.2mm of plastic to hide the screw
<img width="746" height="604" alt="image" src="https://github.com/user-attachments/assets/6d4ed9bd-3ce1-40f6-9611-e7b385169ed1" />
fusion didnt feel as nice on the other side soo i ended up without timeline turned on because fusion wasnt happy
:pf: 
but i got a solution


<img width="1368" height="449" alt="image" src="https://github.com/user-attachments/assets/f5ab35eb-65d0-48fd-ac7b-595966dbd9c3" />
oh yeah the pcb should mount slide into that groove
with the case sliding on from each side

<img width="1585" height="613" alt="image" src="https://github.com/user-attachments/assets/63490f25-7233-40d2-b343-357b58e92de5" />
this is it from the bottom
i just wanted to leave the buttom open because im curious how it will affect the sound of the keyboard





cross section of the solution i eneded up with for mounting the pcb
<img width="2001" height="919" alt="image" src="https://github.com/user-attachments/assets/ad7a8f1a-55eb-4a1b-b892-76816776d135" />








ah yeah the last thing to mention
the omission of any firmware
i plan to use POG and kmk to create a firmware however that requires the physical board
Which is why the firmware is ommitted





