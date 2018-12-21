---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

U.S. flag by Gabriel Ortiz (WIP)

As I said above, this flag is for the United States, I chose this because I wanted to challenge myself. I still have yet to get the rest of the stripes but I have been working a lot in trying to find a way to implement a stripe function, I didn't get it yet so for now I resort to writing a lot of code.


* * *
![Flag](/images/USA.png)
* * *

## Describe your process.

-  My idea was to create all the stripes and then create my flag into 7 different parts. As I created another segment I would use my data from the previous segment and add my new data to see what would happen. I got started but soon realized that I didn't have a lot of time after I kept trying to perfect my collage.
2
layout: post
3
title: "USA!" 
4
date: 2018-12-20
5
--- 





```
include image
WR = rectangle(290,200,"solid","white")
BS = rectangle(200,100,"solid","darkblue")
BS-WR = place-image(BS, 50, 40, WR)
RR = rectangle(290,40,"solid", "darkred")
BS-RR = place-image(BS, 45, 50, RR) 
RR2 = rectangle(290,20,"solid", "darkred")
RR3 = rectangle(290,20,"solid", "darkred")
RR4 = rectangle(290,20,"solid", "darkred")
RR5 = rectangle(290,20,"solid", "darkred")
RR6 = rectangle(290,20,"solid", "darkred")
RR7 = rectangle(290,20,"solid", "darkred")
BS-RR2 = place-image(BS,45,40, RR)
stripe1 = place-image(BS-RR,150,0,BS-WR)

```

* * *

-  WR is the white rectangle which is my background as it would be the easiest to work with for me.
-  BS stands for blue square, I originally made it a square but it didn't fit the parameters so i changed it to a rectangle, I kept the name because I had to deal with the red stripes. I did get the colors right since the flag of the U.S. uses darker palettes than regular colors, giving it a hint of some kind of battle-scarred vibe. I think that's pretty cool.
-  RR stands for red rectangle, I formed them to look like stripes on my flag. I managed to get 1 stripe on but I am still working for the others and how to not get them to overlap. I feel like with more time I would make it better but that would also lead to a more difficult challenge, that being the stars on the flag. 50 in total and I still have nothing for that but I had an idea but I need to review my functions and play around with them for a while.
 


## Program code

```
include image
WR = rectangle(290,200,"solid","white")
BS = rectangle(200,100,"solid","darkblue")
BS-WR = place-image(BS, 50, 40, WR)
RR = rectangle(290,40,"solid", "darkred")
BS-RR = place-image(BS, 45, 50, RR) 
RR2 = rectangle(290,20,"solid", "darkred")
RR3 = rectangle(290,20,"solid", "darkred")
RR4 = rectangle(290,20,"solid", "darkred")
RR5 = rectangle(290,20,"solid", "darkred")
RR6 = rectangle(290,20,"solid", "darkred")
RR7 = rectangle(290,20,"solid", "darkred")
BS-RR2 = place-image(BS,45,40, RR)
stripe1 = place-image(BS-RR,150,0,BS-WR)
```
