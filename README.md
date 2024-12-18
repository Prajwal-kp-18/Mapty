# Mapty

Mapty is an interactive web application that allows users to log and track their running and cycling workouts on a map. Built with JavaScript, it uses the browser's geolocation API and Leaflet.js for map interactions, and stores workout data in the browser's local storage for persistence.

## Features
- Log running and cycling workouts with details such as distance, duration, and cadence/elevation gain.
- Visualize workout locations on an interactive map.
- View workout details in a list format.
- Automatically calculate pace for running and speed for cycling workouts.
- Persist data across sessions using local storage.

## Technologies Used
- **HTML/CSS/JavaScript**: Core technologies for web development.
- **Leaflet.js**: A JavaScript library for interactive maps.
- **Geolocation API**: To get the user's current location.
- **LocalStorage API**: To save and load workouts.

## Usage
1. **Log Workouts**:
   - Click on the map to open the workout input form.
   - Select the workout type (running or cycling).
   - Enter the workout details (distance, duration, and cadence/elevation gain).
   - Click "Submit" to save the workout.

2. **View Workouts**:
   - Saved workouts will appear as markers on the map and as a list below the input form.
   - Click on a workout in the list to move the map view to the workout location.

3. **Data Persistence**:
   - Workouts are automatically saved to local storage, so they persist even after the page is reloaded.

## File Structure
- **index.html**: Contains the structure of the app.
- **style.css**: Styles the app.
- **script.js**: Contains the JavaScript logic for the app.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Open the project in your code editor and start a live server (e.g., VS Code's Live Server extension).

3. Open the `index.html` file in your browser to start the app.

## Contribution
Feel free to fork the repository, submit issues, and make pull requests. Contributions are always welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Prajwal-kp-18 

