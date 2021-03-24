# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nhi Nguyen**

Time spent: **4** hours spent in total

Link to project: https://nhi-prework.glitch.me
Link to view my code: https://glitch.com/edit/#!/nhi-prework

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Adding an image as the background body appearance
- [x] Changing the fonts of the heading 1 and tag

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src="demo.gif" />


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- I use W3Schools to read on how to check all color properties that CSS allows. Then I personally change the colors to the according hex colors I prefer. 
I also used the same source to implement the background body as an image and to change the fonts of the heading and tag. It was interesting to see the family of fonts

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- During step 6 of implementing the switching between Start and Stop button, I was unable to perform that in my code despite constantly checking my code. I tried to backtrack
my code as well as double checking my syntax and my spelling, I was still unable to find the error. I reached out for my friend who had experience in websites before and we 
sat together in trying to figuring out what was the problem. After long hours of screen time, we were still unable to find the error. I finally decided to restarted the program
in a new Glitch program and it worked. I simply continued the project on the new created project. Another problem I ran into was originally I couldn't perform the logic corrctly.
I was incrementing the guessCounter incorrectly and I couldn't figured out why. It turned out to be that I was incrementing it inside a wrong else when the game is still happening.
My solution was to put the guessCounter in another else since it should only be incremented when the guess counter in the pattern list isn't the same as the button clicked. Though 
those times were a bit frustrating, the experience overall was enjoyable because the languages were new to me and it was interesting to use a non OOP language.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- Through this project, I'm more interested in web development. I wonder if HTML/CSS and JavaScript are the only tools needed for front-end web development. What are the languages
being used for back-end developement? How can front-end and back-end interact with each other when they are completely different language? In technical terms, I'm curious on how 
a website is being created with a balance of front-end and back-end because that seems complicated. I'm also curious on how to make a website available for public use since from 
my experience, I can only work on it locally. I hope to have an opportunity to be able to answer all these questions while having hands-on learning and proper guidance.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- If I had more time to work on this project, I'd want to learn how to change the shape of buttons into fun shapes like triangles and circles. I'd also want to add more patterns 
so each time the game starts it will be a random pattern. I also want to add a score system for the player to save their highscores and be proud of their good memory!

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
