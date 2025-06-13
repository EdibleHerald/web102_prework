# WEB102 Prework - The Crowdfunding Tracker

Submitted by: Harold Escorcia

The Crowdfunding Tracker is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 3 hours spent in total

## Required Features

The following **required** functionality is completed:

* [ X] The introduction section explains the background of the company and how many games remain unfunded.
* [ X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X ] List anything else that you can get done to improve the app functionality!

-I added :hover behavior on .stats-card to change background color for more emphasis on the contents.

-I also added border-color and box-sizing on the button filters to add emotion to each option (e.g. unfunded games button being red on hover to show that its considered a bad thing)

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://jmp.sh/FyFP9QIe' title='Video Walkthrough' width='' alt='Video Walkthrough' />


GIF created with ScreenToGif


## Notes

One particular challenge I had was trying to figure out how to deconstruct a dictionary in challenge #7. I was under the assumption that it worked as showed in the background section provided in challenge #7. It took me a while to try searching on my own and I found out that deconstructing a dictionary requires {brackets} and requires either the variables to match the properties of the object (e.g. GAMES_JSON has property description, when deconstructing, variable needs to be named description exactly) OR attribute the property to the variable like you would a dictionary (e.g. const {name: topGameName, description: desc1,...} = GAMES_JSON[0])

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
