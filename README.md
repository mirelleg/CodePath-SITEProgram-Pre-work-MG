# Pre-work - *Memory Game*

**L&S Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Mirelle Sarah George

Time spent: 7 hours spent in total

Link to project: https://glitch.com/edit/#!/fluoridated-lively-gecko

## Required Functionality

The following **required** functionality is complete:

* [+] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [+] "Start" button toggles between "Start" and "Stop" when clicked. 
* [+] Game buttons each light up and play a sound when clicked. 
* [+] Computer plays back sequence of clues including sound and visual cue for each button
* [+] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [+] User wins the game after guessing a complete pattern
* [+] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [+] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/hym2gU7Huw.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Though this is a simple task, I searched up how to use F12 on a Macbook air: https://support.apple.com/en-in/guide/mac-help/mchlp2596/mac
Javascript documentation: https://developer.mozilla.org/en-US/docs/Web/JavaScript
Specifically functions in javascript documentation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge I encountered when creating this submission was remembering to put the semicolon at the end of each line. As context, having had experience with Python, semicolons are not used at the end of the line, as it is used in Java and C++ for example. Therefore, when using javascript and css, I would sometimes forget the semicolon. I overcame this challenge by checking my work over again and making sure that the semicolons were put. I would also test out the output and make sure it correctly worked.

   Another challenge I encountered when creating this submission was that my code would be checking if the player could correctly play the last two clues that was shown instead of the whole sequence. For example, instead of the player having to play the full sequence each time a new clue is shown, it would only check if the player could play the last two buttons of the sequence; if the user tried to play the full sequence, it would show as incorrect if they tried the full sequence if the number of clues shown was at least 3. I had to check my work several times and found that I had extra unnecessary lines of code (context.resume() and var guessCounter = 0) present when it should not be present in playClueSequence(). 

    In addition, a very small adjustment that I encountered, especially because I am not as familiar with html), was that I would type a starting tag and the enclosed statement and type the ending tag without realizing that the ending tag would already be there. Though this is more because I need to be more familiar with html, it is something I noticed a few times when creating this submission.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  - When developing a website, how can one find a good balance between content and design such that the website is insightful and aesthetic but not too boring or too overwhelming?
  - What colors are more aesthetic in web development? What colors should be avoided when designing a website and what colors should be included when designing a website?
  - When dealing with a target population, what are some tips for web development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had a few more hours to work on this project, I would spend some of the time enhancing the overall background instead of just a gray background. This could include images or overall, a more appealing background aesthetic. Adding onto this, another feature I would incorporate is a light or dark mode option. For example, based on a button pressed, the look of the overall website would change; if light mode was pressed, the background would change to white/cream and the colors of the buttons would be darker (when pressed, they would be lighter) and if dark mode was pressed, the background would be what I implemented for this version of the Light and Sound Memory Game. Next, I would incorporate some cool images both when the button is pressed and when the button is not being pressed. In addition, including a progress bar based on the number of the clues in the sequence correctly guessed could allow the player to have a better idea of how far they are in the game. If there were to be 8 clues and the player has correctly gotten through the first two clues, then 2 out of 8 boxes would be colored to show that the player’s progress is 25%. Another addition that I could make to enhance this program is having a random generated pattern by getting 8 random numbers between 1 and 4 and saving that as the pattern. The pattern would be determined as a function before startGame(). This way, the user is not playing the same game over and over again.



## Interview Recording URL Link

[My 5-minute Interview Recording]https://www.loom.com/share/a2767c8296964e28b39d51c55fb89ca9


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
