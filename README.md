# What Do You Meme?

<p align="center"> A cooperative meme based game created for LA Hacks 2018 </p>

![wdym](https://user-images.githubusercontent.com/32719891/38170453-d99a505a-353a-11e8-856c-cc0ae7a35676.png)

What Do You Meme? is a game created to promote friendships through the power of internet meme culture. The game pairs up two players and asks them to react with one three options: ?, Haha, and Yikes. It then uses a carefully thought out algorithm to determine the compatibility between the two players.

## Table of Contents
- [Team Members](https://github.com/gits-lit/lahacks2018#team-members)
- [Purpose and Idea](https://github.com/gits-lit/lahacks2018#overview)
- [Parts](https://github.com/gits-lit/lahacks2018#installation)
- [Demonstration](https://github.com/gits-lit/lahacks2018#demonstration)
- [Additional Credit](https://github.com/gits-lit/lahacks2018#additional-credit)
- [License](https://github.com/gits-lit/lahacks2018#license)

## Team Members
- [Gretal Dea](https://github.com/grtld)
- [Rick Duy Huynh](https://github.com/RickHuynh)
- [Antony Nguyen](https://github.com/eminguyen)
- [Clark Phan](https://github.com/ClarkPhan)
- [Linda Yang](https://github.com/Linda-Yang)

## Overview

In the world of social media and the Internet of Things, it is hard to not be exposed to meme culture and how it has impacted our daily lives and our ways of thinking. Memes have been utilized to market popular consumer products and spread opinions on important global events. Our group had a meme dream and we had the memes and the means to do it. We wanted to harness the influence of this powerful cultural phenomenon and utilize it to connect individuals on a deeper, more memeingful basis.

We attended LA Hacks having taking inspiration from the likes of Kahoot! and The Test and we wanted to match individuals based on their meme preferences. Our application uses sockets.io to live connect users. When two users are connected to the server at once, they are notified and asked if they are ready. Once both users click on the ready button, the game starts.

The game displays various memes and asks users to rate them using our reaction system. Users are given a time limit of 10 seconds to rate a meme before the next one is displayed. Our matching algorithm prioritizes couples who are able to rate memes quicker while also maintaining similiarity. This is a sign that the users are naturally similar people. There is also a hidden time delay to ensure that the users actually take time to read the meme and that they do not cheat.

## Installation

1. If you want to run this project locally, clone the git repository onto your computer.
2. Ensure that you have the latest version of node and npm installed on your computer.
3. ```
   npm install
   ```
   to install the required packages.
4. Run the server using the command 

   ```
   node server.js
   ```
   and go to localhost:3001 to access the website.

## Demonstration

Our application will be hosted on Heroku soon. 

A gif will also be available soon.

## Additional Credit
- [LA Hacks](https://lahacks.com/)

## License
Copyright 2018 Gretal Dea Rick Huynh Antony Nguyen Clark Phan Linda Yang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
