# Travel-Optimizer

Welcome to The Travel Optimizer, created by The Apptimizers!

Our application will allow travellers to quickly plug their destination into the search 
to pull Points of Interest from those cities. One click on that Point of Interest will 
display a photo of that POI, along with a quick description. Clicking on the "Show more 
at OpenTripMap" link below each description will link you to that POI's location on an
external map.

At the bottom of the page, you will find a custom satellite view map for scanning local
POI's. Just click on the location button on the map and allow the map to use your current
location. The map will then let you see nearby lodging, restaurants, historic sites, and more!

Have fun, and Safe Travels!

## Repository

https://github.com/Maryjezek/travel-optimizer.git

## Webpage

https://maryjezek.github.io/travel-optimizer/

![Webpage Screenshot](./assets/images/screenshot.png)

## User Story

```
AS A traveler
I Want to see query locations I want to visit and be able to locate them on a map
SO THAT I can plan a trip to that location
```

## Larger ambitions which were not acocmplished (yet)

Give the time and the coding acutiy, we would have liked to query a map with muliptle points of interest and plot out an itenary. We have accomplished the steps towards that, but it is a bit ambitious to say the least.

The web app utilizes a map API together with an API that returns the attractions in a city. The city results are cliackble, and, when clicked, return two items: on the right is a summary of the attraction and a picture. Below it is the location on a map.

## Description of Code

The webpage utilizes HTML, CSS, and JavaScript in order to perform its tasks. In addition, various APIS and libraries are used

### Materialize

Materialize is used for syling. It has a css library and JS library to perform various styling functions.

### Mapbox

Mapbox is an API and accompaniying JS and CSS libraries, used for the map display.

### Open Tri Map

Open Tri Map is an API which returns local attractions

### JQuery

A JavaScript library for ease of coding

## Features

### Local Storage

Local Storage is first accessed when the application accesses storage to be displayed as past searches.

Local Sotrage is again accessed any time a search is performed, the application accesses local storage and adds the item to the local storage.


Update - Style README text in Word, then copy over.

Update - List API's used in Project

Update with - Add Screenshot of completed project 
