---
title: "🚗 A toy car"
date: 2019-02-11T11:49:20+02:00
draft: true
time: 🕦
---

As a kid I wanted an RC car so bad, took a while but now I have my very own!

<!--more-->
{{<pic oscar_chasis>}}

Hello friend 👋 I bought a Tamiya Mercedes-Benz G 320 Cabrio and I'm calling him _**Oscar**_. First I considered building my own from scratch but it is a lot of work and my focus wasn't in building a car(although putting this one together was already tons of fun), nor is it to show off with kids in the block how cool my new toy is, rather my plan is to modify the car so it can drive itself 🤯.

Yeah so this is all about the hot trending topic of self-driving cars, nevertheless a topic I find quite interesting. I happen to work the industry so I'm constantly following its progress and now I can get even closer this revolution by suffering first hand what it takes to move four wheels in the desired direction. But one step at a time! first the car.

{{<pic oscar_paint>}}

Of course I wasn't going to leave the chassis alone, plug some stuff and call it a day! just because I'm building a prototype doesn't mean the looks don't matter, Oscar has dignity and deserves to look nice, so I continued with the building instructions, found the paint, battery, servo and some tools in a local store to give it the last touches 🎨.

I didn't know what to expect from this Tamiya cars, initially I thought everything I need would come in the box but then discovered what a big industry the RC car models is, they usually don't give you a fully functioning car, people get components separately that can differ greatly in quality and price so it was a fun surprise that I had to build everything painting included. Something that I didn't get for example was the RC transmitter and control(yeah not quite an RC car after all) since it will be a computer driving it, which for now will be a Raspberry Pi Zero W with a wide angle PI camera that I exposed through the front of the car where the Mercedes used to be.

{{<pic oscar>}}

To start simple the electronics will be simple, the standard Lithium Polymer battery of the car that powers the included Electronic Speed Controller can also power the RPI with a step down voltage converter, this batteries give higher voltages that the tiny Pi can't handle. The two analog outputs of the Raspberry should be able to control the steering servo and the ESC with Pulse With Modulation without extra parts. I don't expect this tiny computer to do image processing but should be enough for the initial controlling of the car and streaming the captured video.

{{<pic oscar_parts>}}

I have some ideas on how to structure things and do the coding, I know there are existing projects doing this kind of cars like the [Donkey Car](https://www.donkeycar.com) but I have this bad habit of liking to build things from scratch specially when I'm not fully satisfied with the available options, somehow I often manage to transform the smallest of the projects into a dream of world domination 😂.

To the code! 👨‍💻
