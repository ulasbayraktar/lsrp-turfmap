# LS-RP Turfmap

Turfmap of LS-RP. It may have some minor differences compared to the original codes.

## How can i add Polygon?

After setting the "devMode" parameter to "true" in the HTML file, you can start drawing a Polygon by clicking the Draw Polygon button. Once you finish drawing the Polygon, click the Draw Polygon button again to start filling in the parameters. After completion, press "CTRL + SHIFT + I" or "F12" on your keyboard to activate the Console. You will see the code required to add the Polygon in the console. Take the code you see and add it to the "engine.json.php" file. If you still couldn't do it, watch the video below.

## Image



![image](https://github.com/ulasbayraktar/turfmap/assets/73671806/fbbf0045-d9bf-4420-b085-ed411590687e)


## Video

https://github.com/ulasbayraktar/turfmap/assets/73671806/6e1e099a-5e6b-477b-87d5-767b6c14321a

## Parameters

| Parameter    | Description                                       |
|--------------|---------------------------------------------------|
| id           | Unique identifier of the turf group                |
| name         | Name of the turf group                             |
| color        | Color of the turf group (in HEX format)            |
| thread       | Thread of the turf group (link)   |
| turfIDs      | IDs of the areas belonging to the turf group       |
| turfs        | Coordinates of the areas of the turf group         |
| turfcenter   | Center coordinates of the turf group               |
| turfPolygon  | Polygon area of the turf group (if available)      |
| dimensions   | Dimensions of the turf group (width and height)    |
| limits       | Limits of the turf group (minimum and maximum coordinates) |


