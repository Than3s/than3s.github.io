---
layout: post
title: Quirks of Pacific Drive
categories: gamedesign
---

I'm really not into cars. At all. What I care about is that it can get me from point A to point B, preferably with all tires intact and nothing smoking. All the carburetors (we all know that's not even a real word), engines and... brake liquids just leave me yawning and wanting to run away. Preferably somewhere where they can't get to me in a car.  

Video games are not an exception. I find racing games incredibly boring - well unless you can crash the car into something, intentionally catapulting the driver and make it a nice chain reaction of catastrophes. God, I miss Flatout. But otherwise I just don't see the appeal at all.

<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/BGk2u9-GRTA?si=zKXd5r7kLZBPATM2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>

But Pacific Drive is different. I LOVE the car in the game. During your roguelite style runs through the Olympic Exclusion Zone you dent it, lose your tires and its engine occasionally bursts into flames, but it will always get you home safe. And you feel that you need to repay the favor. So you lovingly change the broken doors, fix the tires and get a better bumper for it. While you're at it, why not paint it red as well? Oooh and you can add some cool racing stickers!

The car in Pacific Drive is more than a tool, it's your lifeline and only mean of transport. And the game puts a lot of effort that you like it and take care of it. It's also a bit... Alive. And that's where quirks come into the picture. 

![My car](/images/auto_drive.png)

## Quirks

Your car is not immune to the horrors of the Olympic Exclusion Zone. Together, you encounter Anomalies, be it simple fields of radiation or Abductors that will just grab your car and pull it several meters, preferably through the trees. My favorite Anomaly so far are those sticky electromagnetic mines, that will attach to your mechanical bestie and make it do random things - turn on the wipers, change the stick to parking mode, scramble your radio or make it accelerate. 

The car doesn't have it easy, and sometimes it just starts manifesting weird behavior. To resolve that you need to put the car into therapy, by finding out what's happening. Here comes the magic of computer therapist!

![Quirk System](/images/PD_quirks.png)

The system is simple - you just find a **CONDITION** of the behavior and its **RESULT**. Very simple **IF THIS, THEN THAT** system. Let me give you an example. 

After returning from a not very successful run for resources, I noticed that my front right door kept opening. That means, I got out of the car, close the door, got back behind the wheel and suddenly CLICK and the door is opened again. Hmm. Took me a while to figure out this might be quirk (since it was my first one and the game is not really good at explaining things) but eventually I put the car into the garage, sit behind a computer and very confidently chose:
> IF FRONT RIGHT DOOR CLOSED THEN FRONT RIGHT DOOR OPENS.

Obviously, that was not the correct answer. The system helps you - it told me I had 2/4 correct. Alright, I'm a game dev QA in real life, this will be easy!

After 10 minutes of jumping on the car, opening every single door, aggressively swerving the wheel left and right the DAMN car kept opening the door. And then I noticed something - the FRONT LIGHTS were ON the whole time! And yep, that was it. 
> IF HEADLIGHTS STAY ON, THE FRONT DOOR OPENS.

Then you just feed the computer some Electronics kit and all is fixed! If the real life therapy would be this easy, the therapist would be without jobs.

I ADORE this system. It made me feel the same as in "real" QA at my job, but just the best part of it - when you see a fascinating bug and then you need to find out what the hell is happening. And you try everything, all the possible combinations and suddenly WHOA, you get it! The devs will be so happy! Well, sometimes. 

Quirks are a great system not only mechanically but also in reminding you, that the car is not only a thing, but it's alive. It's the main character of the game, and you need to take care of it. Quirks are helping establishing a connection between it and you as a player. Can it be annoying? Definitely - I even got the same quirk an hour after this. But that doesn't cheapen the feeling when you solve the first one, and you have the ME SMART moment.