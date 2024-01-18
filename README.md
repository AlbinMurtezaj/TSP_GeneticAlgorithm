# TSP - Genetic Algorithm

## Project Overview
This project is a simple practical implementation of TSP - Genetic Algorithm.

###Requirements

- The program must handle varying number of locations
- The program must take the distances betweeen locations automatically.
- The program must calculate the shortest path possible.
- The program must show the exact road u have to follow to acheive at a location.
- The program must list in order the locations that you have to visit.
- The program must allow to edit selected locations.
- The program must allow to start a new calculation.

## Project Idea
The project idea is that you give a number of cities and the distance between each of them (if they are connected directly), algorithm will find the best possible path to visit each city exactly once and return to the starting point calculating the distance and showing it to you.
## Project Implementation

### Project Structure
**config.js:/** This is a configuration module for the genetic algorithm. Allowing fine-tuning of key parameters, enabling customization and optimization of the genetic algorithm's behavior.
**index.html:/** This file serves as the main entry point for the Travel Salesman Problem Solver application. This utilizes Google Maps and the genetic algorithm to find an optimized route for a given set of waypoints.
**result.html:/** This file is the main file containing the algorithm core and its logic, integrates Google Maps and the Directions Service, all these to solve the Traveling Salesman Problem. 
**style.css:/** This file contains the code that gives style to the HTML attributes.

### Dependencies
**Google Maps JavaScript API:/** https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap&v=weekly

##User Manual
Using it from localhost:
1. **Clone the Repository:**
   - Start by cloning the project repository to your local machine:
     ```
     git clone <repository_url>
     ```

2. **Obtain Google Maps API Key:**
   - Visit the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a project, enable the Google Maps JavaScript API, and generate an API key.
   - Replace the placeholder in `config.js` with your API key.
     ```javascript
     // config.js
     const config = {
         apiKey: "YOUR_GOOGLE_MAPS_API_KEY",
     };
     ```
   - **Note: Be aware that the API Key may incur charges for usage, especially if the website goes live.**

3. **Open Project in IDE:**
   - Open the cloned repository in a text editor or an integrated development environment (IDE), such as Visual Studio Code.

4. **Run the Project:**
   - Launch the project by opening `index.html` in a web browser.

## Using the Application

1. **Explore the Map:**
   - The `index.html` file will display a map with a search bar at the top left corner.

2. **Add Waypoints:**
   - Select locations from the automated options provided by the search bar.
   - Each selected location will be added under the map, showing its name, latitude, and longitude. A marker will appear on the map.

3. **Calculate Best Route:**
   - After selecting locations, press "Calculate Best Route."
   - You will be redirected to `result.html` where the locations are connected by routes and each one is displayed under the map.

4. **Start New Calculation:**
   - To select new locations, press "Start New Calculation."
### Contributors
- [Alban Murtezaj](https://github.com/aalbaan)</br>
- [Albin Murtezaj](https://github.com/AlbinMurtezaj) </br>
- [Arbnore Qorraj](https://github.com/arbnoraqorraj)</br>
- [Dion Kastrati](https://github.com/Dion-Kastrati) </br>
- [Endrit Abazi](https://github.com/EndritAbazii) </br>
- [Leotrim Halimi](https://github.com/leootrimi) </br>
- [Marigona Hamiti](https://github.com/marigonahamiti)</br>

