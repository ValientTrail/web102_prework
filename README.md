# WEB102 Prework - *Sea Monster Top Games*

Submitted by: **Raymond Zegles**

**Sea Monster Top Games** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **20** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.
* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] List anything else that you can get done to improve the app functionality!

Navbar added to allow faster access to Stats and Our Games sections

Search bar added to allow user to search for a game by name

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='./assets/Sea_Monster_Top_Games Demonstration_Raymond_Z.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ScreenToGif 
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

There were a few challenges I encountered when building the app. The first was trying to fill in the code for the addGamesToPage function. At first, I couldn't figure out the way to properly display the game elements in  the template string, but with some help I was able to fix the problem by changing the innerHTML property of my div tag instead of textContent. The second challenge I had was that my VS Code's Github plugin broke and refused to push my changes to my remote repository. I was able to get around that by using Github Desktop to commit and push my changes instead of using the Github plugin. The final challenge I encountered was getting the two bonus features I implemented to fit onto the right spots on the page. I had to split the header up into three parts, header-left, header-right, and navbar-links, each with their own style rules to accomplish this.

## License

    Copyright [2024] [Sea Monster Crowdfunding]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
