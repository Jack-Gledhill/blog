---
draft: true
date: 
  created: 2025-07-23T12:00:00
authors:
  - jack
categories:
  - Hackathons
links:
  - posts/hackupc25_part1.md
  - HackUPC website: https://hackupc.com
  - Wanderlust Devpost: https://devpost.com/software/wanderlust-24eodz
---

# HackUPC 2025 Part 2: The Hacker

HackUPC is Europe's largest hackathon, held at the [Universitat Politècnica de Catalunya](https://www.upc.edu/en) in Barcelona, Spain. 
This year, I was invited to attend with some of my friends from university.

<!-- more -->

!!! info
    For the reader's sanity, this post has been split into two parts.

    - [Part 1](/2025/07/23/hackupc-2025-part-1-the-tourist) discusses the journey to Barcelona and our time there before the Hackathon
    - Part 2 discusses the hackathon itself, including the challenges we faced and the projects we built

## About the Event

### The Sponsors

HackUPC was sponsored by a number of companies, almost all had their own challenges for us to solve:

- [SEAT S.A.](https://www.seat.co.uk)
- [Revolut](https://www.revolut.com)
- [Siemens Energy](https://www.siemens-energy.com/global/en/home.html)
- [Skyscanner](https://www.skyscanner.es)
- [Grafana](https://grafana.com)
- [Vueling](https://www.vueling.com/en)
- [Inditex](https://www.inditex.com/itxcomweb/gb/en/home)
- and [JetBrains](https://www.jetbrains.com)

### The Partners

There were also a number of partners, who mostly provided food and drinks for the event:

- [Major League Hacking](https://mlh.io)
- [Coca Cola](https://www.coca-cola.com/gb)
- [Dominos Pizza](https://dominos.co.uk)
- [Frit Ravich](https://www.fritravich.com/en/)
- [Xurreria Cal Manolo](https://www.instagram.com/xurreriacalmanolo)
- [Risi](https://risi.es/es/)
- [Taller de So](https://www.instagram.com/tallerdeso)

You can get the full details on the [HackUPC website](https://hackupc.com).

### The Merch

There was no shortage of merch at HackUPC.
Every hacker was given a bag full of goodies when they entered that included a t-shirt, a Revolut water bottle and a variety of other items.

![Photo of the Revolut bottle handed out at HackUPC](/assets/posts/hackupc25/revolut_bottle.webp){ width=50%, loading=lazy }
/// caption
Figure 1: The Revolut water bottle handed out at HackUPC
///

### The Food

While the food wasn't exactly Michelin-starred, it was certainly filling and in some cases there was room for seconds. 
There were eight meals in total, spread across the three days of the event. 

While there was an effort to accommodate dietary requirements, they didn't seem to have the most variety. 
That said, there was at least something for everyone. 

<div class="grid cards" markdown>
-   **Friday**

    ---

    :material-food: **Dinner:** Bocadillos

    :material-food-apple: **Midnight snack:** Waffles

-   **Saturday**

    ---

    :material-food-croissant: **Breakfast:** Pastries and bocadillos

    :material-food-drumstick: **Lunch:** Paella

    :material-food: **Dinner:** Dominos pizza

    :material-food-apple: **Midnight snack:** Yoghurt and toppings
</div>

<div class="grid cards" markdown>
-   **Sunday**

    ---

    :material-food-croissant: **Breakfast:** Churros

    :material-food-drumstick: **Lunch:** Hot dogs
</div>

## Registration & Opening Ceremony

The event began with registration at the front door, where we waited in line for a good hour or so.
Once inside, we were handed our wristbands, lanyard and a bag full of HackUPC goodies (including a very snazzy t-shirt).
Our wristbands were colour-coded to indicate our dietary requirements, and included a QR code that was used to check us in and out of events and meals.
While the organisers continued registration, we had an opportunity to meet some of the sponsors and steal the goodies they were offering.

![Photo of the HackUPC 2025 opening ceremony](/assets/posts/hackupc25/hackupc_opening_ceremony.webp){ width=50%, loading=lazy }
/// caption
Figure 2: The HackUPC 2025 opening ceremony
///

After a few hours, it was time for the opening ceremony. We headed there together and took our seats in the auditorium.
The ceremony was opened by the HackUPC team, who introduced the event and gave us a brief overview of what to expect.
There was also a keynote speech from each of the sponsors, who introduced their company and their challenges.

The sponsors also had their own goodies which were given out at their stalls. Revolut had cards for tracking the challenges you'd completed, JetBrains had pins, stickers and tote bags, and Skyscanner had caps.

## Activities & Challenges

HackUPC had plenty of activities and challenges we could participate in during the event. It included things like:

- Workshops from sponsors
- Photo booth
- Nerf gun battle
- Scavenger hunts
- Dodgeball
- Cup stacking
- And a number of other games

I was only able to participate in a few of these, but I enjoyed the ones I did. 

### Find the Biene

Find the Biene was one of the three scavenger hunts at HackUPC. 
The challenge was pretty straightforward: find all 24 bienes (German for "bee") hidden around the venue and take a photo with each one. 
They were hidden quite well, but not so well that we couldn't find them all within a few hours. 

We managed to find all 24 bienes on Friday night, and went to the Info Desk to claim our prize. 
This was a sticker on our lanyard, which was needed to win the Biene keychain. 

![Photo of the Biene keychain](/assets/posts/hackupc25/biene_keychain.webp){ width=50%, loading=lazy }
/// caption
Figure 3: Biene keychain
///

### Photobooth

This was a pretty simple activity. The organisers had setup a Mario-themed photo booth just outside the venue, where we could take photos with our friends. 

### Collect the Sponsor Pins

This was one of the scavenger hunts run at HackUPC. 
Each sponsor got their own set of pins which they could give out to participants. 
Some gave them out for free, while others required you to complete a small challenge. 
I wasn't able to collect all of them, but I did manage to get a few. 

### Activity Lanyard

As we completed these challenges, we didn't just get their respective prizes, but also a sticker on our lanyard for the respective activity. 
If we got three in a row, we got a specific prize for doing so. 
I was only able to get the first row, which rewarded me with the Biene keychain. 

However, the other prizes included previous years' merch and a rubber duck.

![Photo of Jack's lanyard by the end of the event](/assets/posts/hackupc25/lanyard.webp){ width=50%, loading=lazy }
/// caption
Figure 4: My lanyard by the end of the event
///

## Our Project

We decided to build a project for Skyscanner's challenge, which was to use their API to build a travel-related app. 
The project we built was a simple web app that asked users for their travel preferences, then used Google Gemini and Skyscanner to generate an itinerary for them. 
In the end, we called it "Wanderlust". 

You can read more about Wanderlust on [my portfolio](https://jackgledhill.com/about/wanderlust).