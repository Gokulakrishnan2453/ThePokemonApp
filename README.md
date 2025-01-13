# ThePokemonApp
##Overview
The Pokemon App is a simple, interactive web application designed to display Pokemon information. Users can view different Pokemon and their details in an engaging and user-friendly interface.
Project Structure
├── README.md          # Project documentation
├── details.css        # Styles specific to the Pokemon details page
├── home.html          # Homepage of the app
├── pokemon.html       # Pokemon details page
├── styles.css         # Global styles for the app

##Files Description
1. details.css
   This stylesheet contains the specific styles for the pokemon.html page. It includes the layout and styling for the Pokemon details section, ensuring the page is visually appealing.
Key Features:
Styling for detailed Pokemon view
Custom classes for unique Pokemon information
2. home.html 
   This file represents the homepage of the application. It provides an overview of the app and allows users to navigate to view different Pokemon.
Key Features:
Links to individual Pokemon details pages
Clean and interactive design
Includes JavaScript to fetch Pokemon data from an external API (like PokéAPI).
3. pokemon.html
   This page is dedicated to showing detailed information about a specific Pokemon. It is styled using details.css.
Key Features:
Displays attributes like name, type, abilities, and stats
Designed for clarity and easy navigation
Dynamically fetches Pokemon details from the API.
4. styles.css
   The global stylesheet for the app, which applies consistent styling across all pages.
Key Features:
Base styles for typography, buttons, and layout
Shared components like headers and footers

##Tech Stack
HTML5: For structuring the content.
CSS3: For styling and layout.
JavaScript: For fetching data dynamically from an external API.
Responsive Design: Ensures compatibility across various devices and screen sizes.

##Pre-requisites
To run the app locally, ensure you have:
A modern web browser (e.g., Chrome, Firefox, Edge)
Git installed (optional, for cloning the repository)

##Migration & Seed Database Steps
This app currently does not use a database. Future implementations may include database integration for storing Pokemon data.

##Running the App
Clone the repository to your local machine:
git clone https://github.com/your-repo/pokemon-app.git
Navigate to the project directory:
cd pokemon-app
Open home.html in your browser to start exploring the app:
On Windows: Right-click the file and select "Open with" -> Your preferred browser.
On Mac/Linux: Use a file manager or browser to open the file.
JavaScript will dynamically fetch Pokemon data from the PokéAPI and populate the homepage. Click on any Pokemon to navigate to its details page (pokemon.html).
