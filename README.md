# Angela ( COVID-19 )
> A Full-stack application that involves volunteers collecting food, medication or other essential supplies for someone who is self-isolating or vulnerable, and delivering these supplies to their home.
> Live demo [_here_](https://boring-wozniak-c62dd8.netlify.app/#/).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Lessons Learned](#Lessons-learned)
* [MVP](#MVP)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
- Group project, we had a team of 3 and used the scrum framework for the week where we presented our project on the final day. Fully remote where the team utilised VS Code’s live share extension allowing collaborative work on bigger features or supporting one another when tackling problems.

- Local JSON API to add and manage requests
- Geolocation API to get the geographical position of a user
- Nominatim API to acquire the geographic coordinates
- Leaflet maps markers to pin requests on the map


## Technologies Used
- [Javascript](https://www.javascript.com/)
- [Vue](https://vuejs.org/) - version 2.6.11
- [Leaflet](https://leafletjs.com/) - version 1.6.0
- [MongoDB](https://www.mongodb.com/) - version 3.5.9
- [Bootstrap](https://getbootstrap.com) - version 4.4.1


## Lessons Learned
- Virtual DOM 

- External APIs and async Javascript ( Promises, fetch API and error handling ).

- Git Branching and Merging - Getting more exposure creating an isolated environment to try out a new feature and merging it to the develop branch and resolving conflicts that surfaced.

- Scrum framework - As the project only lasted a week we had mini sprints of 2 days. At the start of each morning we had a standup to discuss what we had been working on and what we were going to do today using Trello Kanban giving us perspective on the project. At the end of the project we had a retrospective to discuss what we learned, what we would do differently and what was successful.


## MVP
- The app should will be able to show a list of needs from the people in isolation e.g Groceries, Medication
- The user will be able to edit a specific need
- The user will be able to add a need.
- The user will be able to delete a specific need


## Screenshots
![Project Angela Gif](COVID_App.gif)


## Setup
```
npm install -C client
```
```
npm run serve -C client
```
Runs the app in the development mode.

Open http://localhost:8080 to view it in the browser.


## Project Status
Project is: _no longer being worked on_ ( I'm aware there are issues will be returning to fix them)


## Acknowledgements

- This project wasn't inspired by anything but during our retrospective we found strong similarities with [GoodSAM](https://www.goodsamapp.org/).
- Many thanks to the team [Jun](https://github.com/junInUK) and [Sam](https://github.com/samshum90)

## Contact
Created by [drewpeattie@hotmail.com](mailto:drewpeattie@hotmail.com) - feel free to contact me!


