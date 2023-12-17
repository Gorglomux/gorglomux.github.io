---
title: Pizza Scape
description: An asymetric coop escape game
date: "2021-12-20T20:00:00+00:00"
jobDate: 2022
work: [Game design, Level design, Network Development]
techs: [Unity,Unreal, C#, C++, Zmq]
designs: []
thumbnail: pizzascape/pizzascape-cover.png
projectUrl: 
---

PizzaScape is an asymetric 2-player cooperation game made for PC and mobile. 
One player plays a pizza delivery man with a mobile phone trying to escape a warehouse filled with puzzles, while the other player playing on a fake OS on mobile, helping out by giving clues, using the phone applications like a flashlight....


The game was a project made for the end of my second year of my video game computer science degree, with the special constraint that one player had to be on Unreal Engine, and the other one 
on Unity.

The game was designed to be played locally, and we put some emphasis on immersion by creating an out of the game stressful environnment for the players to be in. Players cannot see the informations each other have, and communication is needed to success.  

We decided to implement the mobile part on Unity, and the PC one on Unreal, and developped a connection with the help of zeroMQ.

For this project I did the network development part, as well as the blockout of the main environnment and the design of the puzzles.