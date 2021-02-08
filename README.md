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
***
1. Clickable Markers to find out the coordinates in info-window:

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/gif3.gif)
***
2. Clicking on the coordinates in the info-window to take you to the directions:

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/gif4.gif)
***
3. Demonstration of Placeable Markers the use of them is given above

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/gif5.gif)

***

You must give the input of the of the coordinates in the file as follows:

1. There must be a route no or the name of the place in the first row

2. And the coordinates in the second row

3. And then make sure to save it as a csv file by using the "save as" option in excel

* The excel file when completed should look as follows

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/img1.png)

* After saving the excel as a csv it should look as follows in plain text you can acheive this by right clicking on the file and clicking on "Edit with notepad"

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/img3.png)

* Finally, the results exported as a csv will look as follows

![Alt Text](https://github.com/Anonymous390/MapTest/blob/main/etc/img2.png)
