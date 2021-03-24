# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Sarah Jamal

Time spent: 4 hours spent in total

Link to project: https://the-memory-game-sarahjamal.glitch.me/

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 


I did not use any outside sources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 


A challenge I faced when creating this submission was creating an account. To remedy this problem, I had to contact the Glitch support team to report the problem. Luckily the problem was solved a few hours after I contacted them, and I was able to work anonymously in the meantime. I also had a problem where the sound was not playing when I clicked any of the colored buttons and the game would get stuck. I solved this problem by looking through the console log provided on safari first and noticed there was a problem with calling the AudioContext(). I have had problems with browser support before and tried Google Chrome next. The same problem was met, in reference to not hearing the audio, but the game was working color wise. I then looked online for problems with AudioContext(), and someone said they had issues with this on Google Chrome, but Mozilla Firefox, works. So, I opened the URL of my game on Firefox, and everything works accordingly. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  
  The questions I have about web development are the following…
     
      1.	What information should web developers be able to recall?
      2.	Can one create their own color hex number?
      3.	Is there one language that is better suited for web development than another? If so, which one and why?
      4.	Why are certain browsers more compatible than others?
      5.	How do you go about developing a website? What is the workflow you use? Is there certain steps you take before others? 
 
 Overall, I think I am most curious with the workflow of the project. How does one know what step has to be done first? I ran into problems that were solved with a browser fix, but I wonder if there was something else that I could have done. I also am curious to know if there is a more desired formatting when it comes to code? After completing this submission, I know what I did to get here, but I want to spend more time understand why I did certain steps, and what would happen if I didn’t.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  
  If I had more time to work on this project, I would love to play around more with adding more buttons and seeing if there was a more concise way to show the code. I also would have loved to analyze code which generated the sound. I will definitely be going back and try to understand that code and where it originated from. I also would have worked to make the website more appealing and look more complete overall. If a website doesn’t draw in its visitor, then they won’t stay. As it is now, the site is very basic and to a normal person may seem incomplete. Adding more features and gameplay would have also increased the time someone would spend on the site and made the game more fun. Perhaps adding different versions of the game would have been nice and allowed for players of all ages to join in on the fun. It would have been cool to add a kids version that helped them to learn animals and the sounds they made, by connecting a picture of the animal on the button to the sound the button makes when the user clicks it. Modifications like this would make the game more playable and also offer different content for different users. 


## License

    Copyright Sarah Jamal

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
