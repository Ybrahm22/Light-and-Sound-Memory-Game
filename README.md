# Pre-work - *Light and Sound Memory Game*

**Light and Sound Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Yug Brahmbhatt**

Time spent: **2** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] Added an alert to indicate # of attempts left

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- The only outside resources I used were documentation. I googled aspects of css, html, and javascript in order to implement the bonus features. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- One challenge that I ran into was implementing the bonus feature that increases the playback speed each turn. It took me a number of trials in order to successfully implement the clueHoldTime function. Since the variable was in milliseconds, I had to be very precise in how much time I took off for each successive iteration. If I took off too much time at each interval, the playback would become so fast that the sound and color change of the button could not be registered. If I took off too little time, there would be no discernible change in the playback through iterations. In order to solve this issue, I had to run it several times as if I was playing the game in order to determine if the user interface ran smoothly. Another challenge I faced was adapting to using Javascript. I primarily use Python and Swift, so it was a little difficult adapting to Javascript. One example was implementing a random pattern. In my experience with Python, it is much easier because I could just utilize the range function, but in Javascript, math.random only returns a value between 0 and 1. In order to find out how to implement this bonus feature, I googled "javascript random number between 1 and 10" and found out that math.random could be used with math.floor to return a random integer.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- During the prework walkthrough I read that different web browsers have different default CSS values. I also realized this for myself when I was trying to add assets to my code. It was much easier to download the asset as a png file from a google chrome extension and then upload it to assets than to download from safari. I want to discover what other aspects change due to different web browsers. I also find it interesting when trying to figure out different ways to express the same thing in different languages, and learning the uniqueness of each language. For example I am taking the codepath IOS course at the moment and learning how to develop apps in Xcode using swift. I mainly work with storyboard layouts so it is interesting to see how these layouts can be modified and achieved with HTML and CSS. I also want to know if there exists such things as constraints in web development, because it is absolutely critical in IOS app development. I feel like learning web development and app development will make me better at both because of the carryover I believe that both will have to my skill set. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- If I had more time I would try to add features that allow users to have more control over their experience. I would like to create settings that allow users to modify the difficulty. I would add features that allow the user to modify the number of squares, modify the speed of the game (adjust playback speed in easy, medium, hard and legend difficulty), allow the user to pick what their buttons look like (squares, circles, piano keys, etc.) and modifying the length of the pattern by allowing it to go up to an infinite number. Instead of winning, the user will generate a score. This would allow my project to become a competitive, high score type of game, which would implement an accessible list of high scores for each difficulty. I think that these changes would make my application more appealing to users. I could also be more creative with the sounds and add different assets for losing, and possibly add some low-playing background music to enhance the appeal of my application.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [YUG BRAHMBHATT 2022]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
