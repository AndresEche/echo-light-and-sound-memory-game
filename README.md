# Pre-work - Echo.

**Echo.** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Andres Echeverri**

Time spent: **5** hours spent in total

Link to project: https://outstanding-wide-chili.glitch.me

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
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] Visible Counter
- [X] Random Pitches chosen every page refresh
- [X] Keyboard Functionality

## Video Walkthrough (GIF)

- Basic Game Functions
![Basic Features](http://g.recordit.co/aUf1DjeBjo.gif)
- Losing Game
![Winning Game](http://g.recordit.co/sIjY2bLw6t.gif)
- Winning Game
![Winning Game](http://g.recordit.co/2zSx9tbRlG.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- https://www.w3schools.com/js/js_htmldom.asp
- https://css-tricks.com/
- https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
- https://color.adobe.com/create/color-wheel

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The most difficult part of the project was working with the Javascript Document Object Model. The biggest challenges came when I decided to implement features not clearly defined in the tutorial. This being the round counter and the keyboard functionality. I started with the round counter. The answer was not clear so to solve this I turned to other resources I had found on google. I was about to go on stack overflow and dedicated JavaScript websites to learn how the DOM works when manipulating element text in HTML. The keyboard functionality was a whole other beast, for this I had to research deeper into how the DOM works when using keyboard input. What I learned was that during an event listener the callback function takes which key you pressed as a parameter and it returns an object that holds multiple properties for the pressed key. I was able to use this to do different functions based on the key registered. Another problem was that you cannot add an “active” pseudo class with a keyboard so I couldn't figure out how to light up the buttons with the key press. What I did was I instead added a “lit” class that had the same properties as the active state. What I took away from both of these experiences is that google acts as the bridge that connects your vision with the final product. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing the assignment, what I mainly was thinking about was how web applications are scaled when working on more complex projects.
My mind went to other successful web applications like Twitter, Youtube, and Facebook. I want to know how to incorporate large amounts of data 
like multiple users' information and incorporate it into a web application. I also want to know the best practices and technologies to optimize a website
to its fullest potential. I have questions regarding the best practices to have when creating a website for desktop and mobile. When it comes to website deployment 
I would also like to know what are the best and most affordable means to do it. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, the main objective I would have would be to convert all the css to be more responsive. I would want to completely
change my style sheet to be able to mold to smaller screens and be functional. I would also like to add a button which changes the theme of the page. I would do this by
having different color classes that would be added and removed depending on which color theme you chose. I would also like to go more in depth with further game features
by adding different difficulties and modes. I would want to create a sound only where one would have to guess based on the sound alone. Alternatively I would add multiple
difficulties which would all change the starting playback speed. Finally I would refactor the code for the button logic to instead be with a switch statement, as it would make the code
cleaner. I would also add functions for repeated code like the logic for what happens when you click and release a button.


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


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
