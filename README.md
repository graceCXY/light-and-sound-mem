# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Grace Chen

Time spent: 4 hours spent in total

Link to project: https://light-and-sound-mem.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![assets/codepath.gif]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I went to w3school to read the documentation of functions such as linear gradient. I also went to Pexels.com to download adorable cat pictures.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Creating this submission had been a fun learning experience! I really enjoyed creating a web project and channeling my artistic energy into the UI design.
	A challenge I encountered in creating this mission is in regards to testing and debugging. After implementing most of the optional features, the program worked as I expected at first, however, after a while, the audio no longer played any sounds. Initially, I assumed that the problem originated from the additional features so I attempted to perform unit testing on every function. I grew increasingly confused as the code did not seem to contain glaring mistakes and main functionalities were mostly intact except for the audio. 
	Then, I tried explaining the entire logic to myself again, suddenly realizing that I had failed to reset the clueHoldTime variable in the startGame such that the clueHoldTime would continue to decrement and persist to later iterations of the game. Though seemingly insignificant, the mistake revealed a lack of attention to the concept of persistence in this project. This problem also reminded me to reset some of the other variables that each produced more subtle errors. 
	Overall, the creation process went smoothly. It showed me that the testing and debugging aspect of web projects are not as purely targeted at visual components as I had initially expected. In addition to systematically learning the way that HTML, CSS, and Javascript interact through the tutorial, I also experienced the project development cycle and especially gained insights into how a project can always be improved. I find the constant learning and innovation especially exciting!

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing my submission, I’m really curious about how I can involve myself with more complex websites and web apps. Comparing this small implementation to the complexity of large, evolved web platforms, I would like to find out how something small can gradually evolve. Some more technical questions I have include interacting with databases, differences between client/server side implementation, storing a users’ information, authenticating logins, as well as development more platform like qualities for people to interact. In addition, I would like to know what particular skillsets I would need to set up something more advanced and exciting as well as how to find the perfect balance of design and functionality. On this note, I’m also very curious about the proportion of time that professional web developers allocate to each aspect of the development cycle and what the typical cycle would look at. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would try to make the game more interesting by developing different levels and variations of the game. For instance, I think it would be interesting to have two game modes: continuous and level-based. In the level-based game mode, the difficulty will gradually increase through decreasing time and increasing the length of the pattern. From a psychological standpoint, people who visit the site may find the sense of accomplishment of visiting the levels desirable. In the continuous model, the game can theoretically go on for a long time until the user makes a mistake. Some variations include displaying all frequencies once and ask users to recall the image based on the frequency. In addition, the audio clip played can be music chords or music of famous composers and, similar to the auditory and memory training, the game can be very educational. I would also try to make this game multiplayer so that it can evolve into a community of people potentially building connections with each other as they train their memory while having fun. Some specific features involve asking users to cooperate to complete tasks and discussion forums of memory tricks. Even though these additional features seem quite ambitious, I believe that some additional exploration and time can enable such possibilities. 


## License

    Copyright Grace Chen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.