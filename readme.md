# NODE.JS APPS

This repo contains simple node.js applications that I built during my studies in the Complete Node.js Developer course delivered by Andrew Mead. 

- **Notes app** - CLI application for writing and managing notes via terminal commands. It utilizes yargs for argument parsing and chalk for styling terminal outputs.
- **Weather app** - Web application for getting current weather data based on location. The app leverages express.js, hbs, and request along with the external mapbox and weatherstack APIs.

# Technologies

- Node.js 14.4.0
- Express.js 4.16.4
- Hbs 4.1.1
- Request 2.88.2
- Chalk: 2.4.1,
- Validator: 13.5.2,
- Yargs: 16.2.0,
- Nodemon 2.0.6

# Installation

- Fork and git clone repo. 

# Usage

- Notes app
    - Cd into notes-app folder
    - Use 'node app.js add --title="[your note title]" --body="[your note body]"' to add a note
    - Use 'node app.js list' to list your notes
    - Use 'node app.js read  --title="[your note title]"' to read a specific note
    - Use 'node app.js remove  --title="[your note title]"' to remove a specific note

- Weather app
    - Go to https://weather-app-dp.herokuapp.com/ 

    OR

    - Cd into web-server folder
    - Run 'npm run dev'
