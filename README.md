# Route Op
***
Route Op (_Route Optimization_) is Python script which helps in to plan your Route to more than one destination in a easy manner.

## Installation
Use the this github repo to download this or use [this](https://github.com/Anonymous390/MapTest "Route Optimization") link to download it. You can unzip the package once downloaded and run the python package manager (pip) to install the modules in the file requirements.txt by running this command
```bash
pip install -r requirements.txt
```
Now you're ready to run the script using the command
```bash
python RouteOptimization.py
```

## Usage
You will be given a prompt from the script to enter the coordinate where you start off from and to enter the name of the csv file where you have rest of the coordinates

Like this:

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/gif1.gif)

The rest of the coordinates will be exported into a csv sheet in the same directory with a map that should open up in your browser. If you ever want to view the same map once again that will be saved in the same directory as well.

The map is based on the google map data. The map has a few features as well:
  * Displays all the coordinates in the csv file on the map numbered in an order.
  * Starting point is display as a marker in blue color and denoted by the letter 'S'.
  * The path you have to follow is marked with a line.
  * If you want to know the coordinates of a particular marker you can click on it.
  * Clicking on the coordinates in the info-window will take you to the directions of the location.
  * Markers are placeable and draggable on the map by clicking on any part of the map as checkpoint or a waypoint.
  * Markers can also be removed from the map by left clicking on them once again.
  * The markers placed by the user are highlighted with yellow in color.
  * You can zoom in and out of the map by scrolling in and out.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
