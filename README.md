# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Efaz Ahmed

Time spent: 3 hours spent in total
![](https://i.imgur.com/gJW9enS.gif)

Link to project: 

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources to help my submission other than what was given by the prompt. Luckily, I've been programming in JavaScript for 6 years 
and am very familiar with HTML and CSS.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenged I encountered in creating this submission was understanding the "tones" and how to implement them. I also was curious on why the volume had to be
between 0.0 and 1.0. Creating the play tone function was slightly difficult only because I've never really dealt with frequency variables and commands such as 
"setTargetTime". Being very new to this concept unfortunately did not allow me to utilize this function to my own extent and being creative with it. The Guess function 
was also a suprise because I first wrote it out in pseudo code but, writing it out was a bit difficult. Luckily, taking my time on it and reviewing my old Java knowledge,
allowed me to perform the Guess function closest to the one provided.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
A big question I have would be how long does a web development project take to do. Even regarding the amount of work needed on the project, I am aware that 
projects go through the software testing life cycle. For example, how long would it take to design a web page that discusses about the "about" section of a
company or product. Possibly could be one to two months even.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would do a lot of things differently and make the game unique to my own liking. I would've implemented images on the colored squares of superhero logos. To add on,
I would've uploaded sounds that are related to the logos. For example a "batman square" would play a dark, ominous sound. I would have refactored the guess function and simply it to less lines of code.
For that, I could use Java streams and compile the code into a one to two lines of code. Additional features would also be choosing different color pallets than the ones given at the start of the game.



## License

    Copyright Efaz Ahmed

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
