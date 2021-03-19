# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **BRENDA PAYAN**

Time spent: **6.5** hours spent in total

Link to project: (https://crawling-ginger-cormorant.glitch.me)

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Link to next game in series with:
  * [x] Player only loses after 2 mistakes (instead of on the first mistake)
  * [x] Game button appearance change goes beyond color (e.g. add an image)

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://im3.ezgif.com/tmp/ezgif-3-f7de46da38f3.gif)
![](https://im3.ezgif.com/tmp/ezgif-3-d77cace686b5.gif)
![](https://im3.ezgif.com/tmp/ezgif-3-726f474ec9c4.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[
- https://www.w3.org/Style/Examples/007/fonts.en.html
- https://www.colorhexa.com/
- https://coolors.co/fafafa-a41623-345511-f5b82e-bfae48
- https://www.w3schools.com/cssref/pr_border-style.asp
- https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array
- https://www.codecademy.com/forum_questions/54ee385086f55223510004d6
- https://stackoverflow.com/questions/2738920/how-to-add-background-image-for-input-type-button
- https://www.w3schools.com/cssref/pr_font_font-size.asp
- https://stackoverflow.com/questions/53821242/javascript-how-to-count-down-attempts-and-alert-after-certain-number-of-attempt
]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[Immediately after beginning my submission,  I noticed that HTML and CSS are notably different from Python, the programming language I am most familiar with. One of the most difficult aspects was not only learning how HTML, CSS, and JavaScript work together, but also trying to interpret the syntax in a way that I could use it in other projects in the future, instead of just obtaining a surface-level understanding specifically for this game. I felt that CSS was pretty self-explanatory; however, HTML and JavaScript were completely new to me. One of the biggest challenges was altering the guess function in order to count the number of mistakes and set a limit of two mistakes before the loseGame function was called. Initially, I tried to use the same technique as the guessCounter, but that made the game stop functioning. Next, I tried to add a new else command within the guess function, but I continued to get errors, which I later found were a result of not having proper curly brackets. Nevertheless, this method did not work even after fixing my bracket issue. At this point, I was a little disheartened that I couldn’t figure it out, but I took a short break and reflected on the techniques I was trying. It was then that I had an epiphany: I needed to shift my mindset from “solve the problem” to “understand the problem”. I did some research and made sure I completely understood how each of the functions I was calling worked, and how counters were used by other programmers. I carefully read through different methods and thought about how I could apply them to my game, and found that instead of having the counter work up (“counter”++) I could have it work down (“counter”--). I could then set my mistakeCounter variable to a certain number and call the loseGame function when the mistakeCounter was equal to zero. I was stunned at how quickly I was able to develop a solution after thoroughly analyzing what I had tried, and paying more attention to the problem itself rather than solely focusing on obtaining a solution. As I kept working, the process of finding a solution became more gratifying than just finding the solution itself.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[
- Would developing a programming language that combines the three functions of the languages used here (JavaScript, HTML, CSS) be plausible? 
- How is the syntax of each (HTML, CSS, JavaScript) translated/combined into one web page by the computer?
- Are encryptions/protected data on a website created using JavaScript?
- What traits (functionality, visual design, etc) define good web development?
- How are web pages protected from hackers (or can a website be damaged solely through HTML)? I was trying to limit the time players on my game had to click a button, and on accident I made the time interval too short so the pop-up alert would not go away. While troubleshooting, I found you can see the complete html of a website by right clicking > Page Source or CTRL + U. 
- In Python, I’ve learned to import modules to introduce different commands in my coding projects. An example of this is the “math” module to use functions like “math.sqrt(x)”.  Is there an option to import modules like this in JavaScript to use in web development applications?
- Are there any major drawbacks to using cloud computing for web development? 
- I have not worked on any huge app/web development projects that required data storage beyond the storage provided on my computer/github. Is it standard for web developers/programmers to need to use larger platforms like MongoDB for data storage/management? If so, how do you decide what platforms are best to use?
]


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[Overall, I would make it more interactive and fill the extra space I have on the webpage:
- To help with the interest of the webpage, instead of each button just flashing a color when it is clicked on, the icon could actually move or “pop” out, or some kind of character could “grab” the ingredient.
- In terms of filling the extra space, I could either add more ingredients (more buttons, taking up more space, making the game more difficult) or design a better background. 
- I could develop multiple other “recipes” for the game, each with their own color scheme, graphics, etc, and maybe add multiple levels for each recipe. The first level would be remembering the order of the ingredients, the second would be remembering the steps involved in combining/baking/cooking the ingredients, and the third could be arranging toppings/garnish/decorations in a certain way. The player could then move on to the next recipe, which ideally would be more difficult than the first. 
- I have some experience with Adobe Illustrator and I think I would also like to draw the graphics on my own and include them - it was difficult to find graphics with the matching background colors, and when I did find them with matching backgrounds, my selection was extremely limited. 
- I think it would be cool if the cursor was an image instead of just the pointer - I have seen examples online where the cursor leaves a trail of bubbles or sparkles, or is an image. 
- I would also like to add a “menu” page where players could see all recipe options upfront, and their associated difficulties. 
- Adding some kind of sound that differentiates the ingredients would be interesting.]


## License

    Copyright [BRENDA PAYAN]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.