# ExploreEase

ExploreEase is an advanced travel companion application designed to enhance your travel experience. It uses geolocation to recommend nearby restaurants, hotels, and attractions.

## Features

- **Geolocation Services**: Locate your position using Google Maps API.
- **Place Searches**: Find restaurants, hotels, and attractions near your location.
- **Real-Time Data**: Recommendations fetched dynamically via RapidAPI.
- **Responsive Design**: Built with Material-UI for a seamless user experience.

## Demo

Explore the live project here: [ExploreEase on GitHub Pages](https://sanskriti-lal.github.io/Explore-Ease/)

## Technologies Used

- **Frontend**: ReactJS
- **API Integrations**:
  - Google Maps API for geolocation and place searches
  - RapidAPI for fetching location-based data
- **UI Library**: Material-UI
- **Deployment**: GitHub Pages

## Installation

Follow these steps to set up the project locally on your machine:

### Prerequisites
1. Install [Node.js](https://nodejs.org/) (version 14.x or later recommended).
2. Install [npm](https://www.npmjs.com/) (comes with Node.js).
3. Obtain API keys for:
   - **Google Maps API**: [Get your API key here](https://console.cloud.google.com/apis/credentials).
   - **RapidAPI**: [Get your API key here](https://rapidapi.com/).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sanskriti-lal/Explore-Ease.git
   cd Explore-Ease
2. Install the project dependencies:
   ```bash
    npm install
3. Set up environment variables:
    - Create a .env file in the root directory of the project.
    - Add the following variables to the .env file:
      REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
      REACT_APP_RAPIDAPI_KEY=your_rapidapi_key
    - Replace your_google_maps_api_key and your_rapidapi_key with your actual API keys.
4. Start the development server:
   ```bash
   npm start
