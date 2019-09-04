---
title: "🖥 I built a PC"
date: 2018-12-05T09:53:37+02:00
time: 🕙
draft: false
---

It's always exciting to build a new computer isn't it?

<!--more-->
For several years I was more of a nomad, carrying _compuberto_ all around, my usual 13 inch laptop that has seen a few reincarnations due to misuse 😅, _compuberto primero_ had an invasive surgery and never was the same again, _compuberto segundo_ turned out to dislike German beer and _compuberto tercero_ just suffered a sudden heart attack. That's probably the last Asus Zenbook that I'm getting and the end of the dynasty. Other than that at home the closest thing to a desktop I had was a raspberry Pi used cheap WiFi router, time for a decent set up!

## What I need
So what kind of computer should I build? Let's review some requirements.

- **Penguin friendly 🐧**  
Easy to fulfill, I use Arch Linux, end of the story. That means the usual **x86-64** architecture like any modern PC.

- **Developer friendly 👨‍💻**  
I create and use software that should be running all the time, may run several virtual machines/containers or (cross)compile code on automated regular basis. All good excuses to get a enough **memory** and  **CPU** cores!

- **Data processing 💽**  
Often toying with big enough data-sets is a clear call for **fast storage** 😏.

- **Big tiny data 💾**  
I want to store my WHOLE life there, no more personal data spread all around world's evil corporations! I need **massive storage**, like a couple of gigs big!

## What I got

{{<pic pc>}}

Once I carefully identified what I "need", I arrived to the logical conclusion I have to get a nice modern computer(_cough_... excuses!), but let's start simple.

- **CPU: _AMD Threadripper 2920x_**  
Processor is basically the only thing to decide here, first I thought of a server CPU but server components are usually more expensive and bigger. A high end desktop CPU? then I came across Threadripper family, best of both worlds! It will be a while until I really need tons of cores so I'll start with something in the middle, the 12 cores(24 threads) of the 2920x will feel great compared to the laptop CPU that I'm used to and knowing I can bump it up to 64 threads eventually(2990wx) makes it feel like a solid choice.

- **Main board: _ASRock X399M Taichi_**  
Easy choice, the only choice 😅. I wanted a powerful computer but also a compact one, and the only microATX sized board for the Threadripper was this cute board.

- **Case**  
There is something very appealing and sexy about exposed electronics don't you think? I wasn't going to get a case in the first place but then found a nice looking microATX aluminum frame that would fit perfectly in my cabinet and help held together the board and the quiet power supply for easy moving ❤️.

- **RAM: _2x16GB DDR4_**  
Unless I'm running something heavy like virtual machines or playing designer I really don't need much RAM, when it comes to my workstation the system dependencies are counted and I keep everything as lean as possible. I can fit 4x16Gb but 32Gb will already be more Firefox tabs than I can count.

- **Storage: _Samsung NVMe 970PRO 512GB x2_**  
Before getting into my PC building adventure I didn't know about NVMe and the M.2 form factor, we leave in the future! 🤯 those tiny drives are great, I can install 3 of them so I thought of having a RAID 5 for extra redundancy and possible data recovery but until Btrfs, my file system of choice, doesn't fix the issues it has with this kind of arrays I won't bother and have a RAID0 with two drives that are more than enough to store and swiftly retrieve my non existing digital life.

- **Cooling**  
Computer had to be quiet, I don't want a constant buzzing noise in my dreams, liquid cooling seemed very appropriate 😌 I liked Corsair options, I was about to get a small single fanned radiator that was probably more than enough but then my hesitance betrayed me, what if later I get the bigger Threadripper and I'm computing the meaning of life and the smaller radiator isn't enough? two fans and long radiator it is!

- **GPU**  
I naively expected the main board to have integrated graphics but then realized that people don't build a high-end gaming looking PC to use cheap graphics, but I really don't care for now about 3D accelerated fanciness, my PC gaming days are gone and there's nothing fancy about my desktop environment, I just wanted to plug a monitor and keyboard to the computer and get started! Luckily amazon was one tab away and getting the cheapest used GPU delivered the next day was easy.  
Some time in the not so long future I'll consider buying a decent GPU in case I want to train machine learning models for a few projects I have in mind or perhaps rendering a complex cube filled scene in blender. Some day.

Now was the time to plug my Archlinux loaded USB drive and set up a simple containerized workstation(more on that some day 😆) that I could access from the remote 5 meters away comfort of my bed.
