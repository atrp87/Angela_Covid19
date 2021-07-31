# COVID-19 Project Angela
[[Live Version]](https://boring-wozniak-c62dd8.netlify.app/#/)

A Full-stack application that involves volunteers collecting food, medication or other essential supplies for someone who is self-isolating or vulnerable, and delivering these supplies to their home.

* Local JSON API to add and manage requests
* Geolocation API to get the geographical position of a user
* Nominatim API to acquire the geographic coordinates
* Leaflet maps markers to pin requests on the map

![Alt Text](COVID_App.gif)

Group project, we had a team of 3 and used the scrum framework for the week where we presented our project on the final day. Fully remote where the team utilised VS Code’s live share extension allowing collaborative work on bigger features or supporting one another when tackling problems.

### Lessons Learned:

Git Branching and Merging - Getting more exposure creating an isolated environment to try out a new feature and merging it to the develop branch and resolving conflicts that surfaced.

Using the Scrum framework one of our instructors acted as a product owner but we created the backlog ourselves and picked off user stories to plan each sprint. One of us acted as a Scrum master to manage the work we were doing.

External APIs and async Javascript ( Promises, fetch API and error handling ).

## Built With
* [Javascript](https://www.javascript.com/)
* [Vue](https://vuejs.org/)
* [Leaflet](https://leafletjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [Bootstrap](https://getbootstrap.com)

## Project setup
```
npm install -C client
```

### Compiles and hot-reloads for development
```
npm run serve -C client
```
Runs the app in the development mode.

Open http://localhost:8080 to view it in the browser.

### Compiles and minifies for production
```
npm run build -C client
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

