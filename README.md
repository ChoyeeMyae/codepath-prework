# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Choyee Chan Myae**

Time spent: **8** hours spent in total

Link to project: https://glitch.com/edit/#!/messy-surf-scorpion?path=script.js%3A15%3A24

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
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/pHeCco3.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
* https://pages.mtu.edu/~suits/notefreqs.html
* https://www.w3schools.com/cssref/css_colors.asp
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/ceil
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
* When I started reading the pre-work, I thought it would be hard to accomplish because I have not yet learned HTML, CSS, and Javascript. But the guide showed how to implement the code step by step which was very straightforward and helpful. The biggest challenge I faced was the game logic because that function is the only thing we needed to do by ourselves without looking the hint provided. First, I looked at the game logic flow chart and simply wrote 3 if statements: if (guess is not correct), if (turn is not over), if (this is not the last turn). Then I thought about how to turn that into code and wrote the code for each of those cases. As I progressed in writing the code, I also checked with console logging to debug my code by printing guessCounter, progress and pattern[guessCounter].  Breaking a large task into smaller steps helped me with overcoming this challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* I would like to know more about how this project relates to a real-life job. I want to know more about the daily life of a web developer. Even though this is my first time learning HTML, CSS, and Javascript, I had fun and want to learn more about it. This was also my first time using Github, which was interesting to learn about. What other languages and technologies can be used by a web developer? How do front end and back end technologies interact?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
* If I have time, I would like to create the pattern as randomly selected real songs (like Never Gonna Give You Up by Rick Astley). I like to add a hint button that users can use a maximum of 3 times. The hint button will light up or blink. I also would like to add a function that will display when the user wins the game where all the buttons will light up randomly and play a happy song. Similarly, when the user loses the game, it will play a sad song. I also would like to add the advanced difficulty mode that activates when the user wins. The advanced difficulty feature will add more buttons to the game, and have a turn time limit that speeds up as the user plays.


## Interview Recording URL Link

[My 5-minute Interview Recording] https://www.loom.com/share/37f50076de65445784053799a1d5802c


## License

    Copyright [Choyee Myae]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
