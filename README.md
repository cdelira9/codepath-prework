# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Cynthia Delira

Time spent: **#** hours spent in total

Link to project: (https://glitch.com/~delira-prework)

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
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/EgjkKRIuDt.gif)
![](http://g.recordit.co/Y0wR1cPJ26.gif)
![](http://g.recordit.co/O964KRcYfT.gif)
![](http://g.recordit.co/b8EJWvqrn1.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

Websites used: W3schools.com, support.glitch.com, pinterest.com(for pictures)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

Working with this challenge was enjoyable as I was able to learn more about HTML and CSS and with the help of outside resources I was able to implement additional aspects to the game. One challenge I faced was adding images to the buttons. When I first began the challenge I took a similar approach to the background image and added the image to the the javascript file which only led to confusion as I was able to upload images to the webpages but I was unsure how the pictures to only pop up when the button is clicked or active instead of the button changing color. Using outside sources like w3schools I was able to learn that I can simply add a background image in the css file in the active button function that has already been created. This was very useful as it made adding and altering the buttons much easier. Another challenge that I faced was the addition of a fifth button. Creating this button was a challenge since I overlooked a simple error in which I miswrote a piece of code for the fifth button. When creating the fifth button I made sure to repeat the steps that were done when creating the other four buttons and even assured that the fifth button was included in the pattern sequence yet when I rewrote the active function I made a grammatical error. Due to this error when the pattern would be displayed and instead of showing that the fifth button was next in the sequence it would instead show nothing. This led to my first reaction to believe that something was wrong with the pattern sequence since it would stop showing the pattern or as I thought. I did not see anything wrong with the code so I decided to try clicking the fifth button in place of the blank space which I then realized that the button was not changing its image when it was its turn in the sequence. This led me to its active code which I realized had a grammatical error and was able to fix this mistake that I overlooked.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

Regarding web development I am curious to know how and why websites crash when there is an overload of users on the website. An example being ticket selling websites like TicketMaster which tend to crash when there are thousands of users going after the ticket same ticket but even with the queue in place it still crashes and I am curious to know how this happens and what are limits of these websites and does it depend on the sites and how many users they can support. In addition to this I would like to learn why some websites become slower after some time and what causes the lag. Is it because of an overload of users? Does this occur when the site has too many features that require a stronger internet connection? Completing this submission has filled my curiosity to think of other sites that I use on a daily basis and also question the problems that I have encountered with them and ask why this occurs. But working on this submission has also filled my curiosity to different features of these sites and wonder how I can implement these. An example being when users are able to create an account and log in to their account in a website. This makes me wonder how this is created and where all these accounts are stored.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had more time to work on this project, one feature that I would love to work on is a record sheet that saves the amount of times the user plays, the total of wins, total of loses as well as their winning streak. I think this would be fun to include specifically the winning streak since it creates a more enternatianing game since the user is determined to increase their streak but make sure not to lose it. A second feature that I would love to spend more time on is to create customizable buttons. Since my submission I was able to select certain kermit images that have been used in various memes. I think it would be fun for the users to be able to customize their own buttons by uploading their own images to the buttons. 



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Cynthia Delira

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
