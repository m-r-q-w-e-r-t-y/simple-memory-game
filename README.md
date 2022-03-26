# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Anthony Mendez**

Time spent: **2** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/wlBMTUz.gif)

## Reflection Questions

1. **If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**

- N/A. Did not use outside resources.

2. **What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

- Developing the `guess()` function was not as straight forward as I initially thought. After using console log to debug, I was able to get the solution working. I opted to use the solution provided. It was understandle and more concise than my implementation.
- Another challenge that I encountered was developing the timer functionality using `setInterval` and `clearInterval`. To implement it, I had to look at the MDN Web Docs to get an understanding of what each function is and how it is generally used. To get a better undstanding of how it is used in practice I watched Ania Kubow on [YouTube](https://www.youtube.com/watch?v=GhePFBkdNYk&t=127s). After a couple of tests runs in my code, I got a working implementatino running.

3. **What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**

- My main question is how are companies able to keep track of so much code when making a product. Even for this project, 129 lines in the backend and even more for the frontend is a lot to keep track of. What are the methods that the industry uses to make coding easier to develop off of.

4. **If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**  
- What first comes to mind is that the ending message function could be refactored to display "You win" or "You lost". Also, I would add a functionaly that gives the user a random pattern to follow along with the option to increase the speed of the game. Finally, I would add even more CSS to make the web site have a more modern feel to it.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://buffalo.zoom.us/rec/share/KSJ1SZH-xuaJXZ4__SOk4iL3dlHoFvam1jEyU8UWXaz4l6IubLEQcep5yqpvKUIq.99O_JI-BGQ9hYnSf?startTime=1648137157000)

## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
