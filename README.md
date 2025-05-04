# WEB102 Prework - *PlayForge.com*

Submitted by: **Quan Tran**

**PlayForge.com** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] Added a search bar that lets users search for a game by name.
* [ ] Displayed a "Funded" badge on games that have met or exceeded their funding goal.
* [ ] Improved the CSS styling to make the site more visually appealing (e.g., hover effects, spacing, fonts, or card layout).

## Video Walkthrough

Here's a walkthrough of implemented features:

<p><a href="https://www.loom.com/share/ab7941c1ff27488287bd1d0b12040478" target="_blank">🎥 Watch the video walkthrough</a></p>

Video created with Loom

## Notes

Challenges Encountered While Building the App

While building the Sea Monster Crowdfunding app, I encountered a few key challenges:

### 1. DOM Manipulation with Dynamic Data  
Managing the dynamic rendering of game cards based on filtered data (funded, unfunded, all) required careful use of functions like `filter()`, `forEach()`, and clearing previous content using `deleteChildElements`. Ensuring each update reflected accurately on the page without duplicating elements took some trial and error.

### 2. Ternary Operators for Dynamic Text  
Writing grammatically correct summary messages (e.g., "1 game remains" vs. "2 games remain") using the ternary operator required logical precision to ensure proper grammar and pluralization.

### 3. Sorting and Destructuring Data  
Sorting the games by funding amount and using destructuring to grab the top two funded games involved understanding how to work with arrays and maintain order after sorting.

### 4. Implementing Bonus Features  
Adding a real-time search bar and conditionally displaying a “Funded” badge introduced new layers of DOM manipulation. These features pushed me to think more deeply about how UI components respond to dynamic data.


## License

    Copyright 2025 Quan Tran

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
