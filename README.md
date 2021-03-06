# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Tim Tu**

Time spent: **1** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/coffee-spurious-elbow)

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
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
[Imgur Link](https://i.imgur.com/o1tmvQd.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

[w3scholars for some help with changing inner html]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

[I initially forgot to return after implementing strikes, so there were odd issues with the sequence not being continued. For this part, I ran into the bug after
trying to correctly get the sequence after an incorrect run. I realized that the issue was with processing incorrect guesses as it wasn't an issue without strikes. After looking back at the code
I realized that the guessCounter and progress counter were still being updated after an incorrect guess when they shouldn't have been.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

[I mostly have questions about modern frameworks that people use instead of just HTML, CSS, JS. After having done a few projects with these tools, I realize that it's pretty difficult to create something practical
and good looking with the barebones tools. I'm curious as to how people figure out what to bootstrap with and essentially where to start before adding original code and ideas. ]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

[I would probably spend some time updating the CSS for the text fields as well as their layout. I would also want to add more customizability for the layout and gameplay. i.e adding the
length of the sequence to memorize, number of buttons you can use, hints, and so on. Additionally, I may want to try updating when / how buttons are clickable since they are currently clickable during the
clue phase which allows the player to get rather confused if you do it during that time and sort of lose the flow and tempo. On another note, I may want to add customizability for colors and sound for usability, as users may be
color-blind, hard of hearing, etc.]

## License

    Copyright [Tim Tu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
