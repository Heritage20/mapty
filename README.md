# Fitness Tracker App

This repository contains the code for a Fitness Tracker App that allows users to track their running and cycling workouts. The app utilizes HTML, CSS, and JavaScript to provide an interactive user interface and uses the Leaflet library for displaying the map.

## Features

- User can add new running or cycling workouts by providing the distance, duration, and other relevant details.
- The app displays the workouts on a map as markers and provides a popup with workout information.
- Workouts are categorized as either running or cycling and are visually represented with different icons.
- For running workouts, the app calculates the pace (minutes per kilometer) and cadence (steps per minute).
- For cycling workouts, the app calculates the speed (kilometers per hour) and elevation gain (in meters).
- User can click on a workout to zoom in on the location on the map.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/fitness-tracker-app.git`
2. Open the project folder: `cd fitness-tracker-app`
3. Open the `index.html` file in a web browser.

## Usage

1. Upon opening the app, the user's current location will be retrieved (if allowed) and displayed on the map.
2. To add a new workout, click on the map at the desired location. A form will appear where you can enter the details of the workout.
3. Select the workout type (running or cycling) and enter the distance and duration.
4. Depending on the workout type, additional fields may appear for cadence (for running) or elevation gain (for cycling).
5. Click the "Add Workout" button to add the workout to the map and the workout list.
6. The added workout will be displayed as a marker on the map with a popup showing the workout information.
7. To view a workout's location on the map, click on the corresponding workout in the workout list.
8. To reset the app and delete all workouts, you can call the `reset()` method in the browser console or refresh the page.

## Dependencies

The app utilizes the following libraries:

- Leaflet: A JavaScript library for interactive maps. It is used to display the map and handle map-related events.
- OpenStreetMap: A free and open map data source used by Leaflet to provide the map tiles.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for personal or commercial purposes.
