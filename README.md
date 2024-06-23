# arcgis-esmodules-cookbook

## Description
Small webapp with embedded ArcGIS maps.

The project showcases how to embed an ArcGIS map in a webapp using React+TypeScript and the ArcGIS Maps JavaScript SDK.
Powered by vite and testing is done in vitest.

## Available Recipes

### [Layers example](src/scenes/NewZealandScene/readme.md)

### [Basemap example](src/scenes/SantaMonicaScene/readme.md)

## Running the app locally

### Prerequisites
1. You will need to create an ArcGIS developer account and generate an API key for yourself
   Here is the link: https://developers.arcgis.com/dashboard/

2. Add a .env file to your project root folder and add the API key as follows:
   VITE_ARCGIS_API_KEY= `<your api key here without quotaion marks>`

### Install
Clone the repository and in the project root folder run the following command from the terminal:

`npm i`

### Run
After installation, in the project root folder run the following command from the terminal:

`npm run dev`

## Live version
The app is deployed here if you just would like to have a look:
https://agi-arcgis-map-viewer.vercel.app/

## Supported browsers
The app was manual tested in Firefox, Chrome, Safari and Brave browsers, both mobile and desktop.
