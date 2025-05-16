---
title: "Designing A Back"
date: 2025-04-07
---

## Graflex 4x5 Back (slotted)

It only makes sense, for me to start at the film. Film has to be held, and given the theme of what I'm trying to do here I'm starting with a 4x5 film holder and camera.

I won't bore a reader with some history on photography, plates, film, etc. that's all researchable. I have found it curious that to the best of my searching I can't find STL files for the wooden graflex 4x5 holders for a graflex SLR. 

I happen to have a graflex SLR and 3 old wooden holders for it with grooves - they seem to either be rare, or difficult to search for, and many people replace the old metal rails these film holders fit on with a springloaded back or mechanism from a later camera.

Personally I don't love that, so I'm just going to sacrifice one of my film holders to get the dimensions and try to make plans to 3d print on of these. Again, Graflex was able to do it with cherry and hard work, I have digital calipers and a 3d printer, so it should be easier for me. But we'll see.

### How do they work? 
At it's core, this is simply a wooden box that you slide film in one direction and a dark slide in the other. This way you don't accidentally remove the film when you remove the darkslide (although that happens unfortunately). When it comes to film holders, the only real requirements are that the film is the right distance from the registration surface, and that it's light tight.

### Registration distance
A quick google will tell you that the film goes 5mm from the front surface of the film holder to ensure proper focus. That struck me as odd, to the best of my knowledge Graflex was the 4x5ing-est company there was and William Folmer (the founder) was as American as it gets and 1887 was no time for a red blooded American manufacturer to be using millimeters. In freedom units, this is 0.197 inches. This also seemed goofy at first to me, but the more I thought about it, that's just 3 thou shy of 1/5th of an inch. _That_ sounds like some big dick show off miniturization for an American at the dawn of the 20th century! It also appears that the registration surface to where the "septum" sits is ~0.248 inches which feels like they were targeting a quarter inch at some point in this process as the thickness for a single sided film holder and double sided ended up being the design that won out.

### Light tightness
Light hates corners, and you know what else it hates? felt. These old wooden holders the graflex SLR uses don't have the ridges of later holders to lock in place, nor the tall edges to generate that many corners, but the film holder does sit flush against felt. There's plenty of corners around the sides of the film to stop the light, but I had often wondered before starting this, how do you prevent light leaks where the darkslide goes in? Wouldn't you know it, sheet metal bent in a V shape with felt on it. The sheet metal is simply glued into place. What a masterpiece of simplicity.

### Joining the wood
Wouldn't you know it, the holder is joined together with simple 19 gauge, 5/16" brad nails, nothing fancy.

### How they probably made it 
A sheet metal fabricator would have made the septums, light traps, and darkslides I assume. The bodies were 5 pieces that I can tell: a frame side, frame top, frame bottom, two bottom darkslide holders, and two finishing pieces on the top. It appears to have all been joinery except the glue to hold the light traps in and the brad nails to hold the trim on the top. 

## Redesigning for 3D printing

We have some options here, obviously we should be able to 3d print better than someone could have done woodworking in 1910, so we could just exactly copy the wooden design. More recent 4x5 holder designs are entirely plastic and are made in layers with locating pins that are then welded or glued together making them virtually impossilbe to take apart to examine. Though some patent drawings do exist.

I do own one hybrid plastic and metal film holder that appears to be a plastic shell with a metal center shoved into it. Maybe that's a useful data point. 

So there's our options:
1. Copy the wooden one
2. Horizontal sandwich like new ones
3. Shell with insert

### Support minimization
I hate support material. It basically ruins the printing experience in my opinion because I really don't want to waste time cutting the supports off and it ruins the dimensional accuracy that we do have. Probably the best bet will be to model the frame with septums in place, print the top finishing pieces and bottom locking pieces separately. And glue/tape them together. It won't be the most efficient thing in terms of materials and print time, but will probably work best.
