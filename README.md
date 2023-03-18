
# GeoCapture

Are you in need of a simple, web-based solution for capturing geographic information without access to a GPS device? Look no further than the GeoCapture!

This interactive map provides a range of base maps to choose from, and enables you to easily capture the coordinates of locations of interest. With just a few clicks, you can set markers, add descriptions, and save your data in a convenient CSV file.

Built using HTML, CSS, and JavaScript, the GeoCapture leverages the powerful Leaflet library to create and display the map, and uses the Proj4js library to convert latitude and longitude to Universal Transverse Mercator (UTM) coordinates.

[![Live Preview](https://img.shields.io/badge/Live%20Preview-View%20Now-brightgreen)](https://aminbeheshti.com/projects/geocapture/)


## Features

-   Interactive map with different base maps to choose from.
-   Geolocation functionality enabled to find the user's current location.
-   Ability to set markers and get the latitude, longitude, and UTM coordinates of the location.
-   Table to store the location information, including description, latitude, longitude, and UTM.
-   Ability to add description to the points and delete them in the table.
-   Option to save the information in a CSV file.

## How to use

Using GeoCapture is simple:

1.  Clone or download the repository to your local machine.
2.  Open the `index.html` file in your web browser.
3.  Allow the application to access your location if prompted.
4.  Click on the map to set a marker at the desired location.
5.  Enter a description of the location in the table.
6.  Edit or delete the location information as required.
7.  Click the `Save to CSV` button to download the location information in a CSV file.

## Why I made this tool

I created GeoCapture with the goal of providing an easy-to-use tool for anyone who needs to collect geographic data without access to professional GPS equipment. Whether you're out in the field without your GPS, or simply prefer to use your phone or computer to capture location data, this tool provides a simple and effective solution.

## Contributing

Contributions are welcome! If you find any issues with the code or have ideas on how to improve it, please feel free to submit a pull request or open an issue.

## Credits

GeoCapture was built using the following libraries:

-   [Leaflet](https://leafletjs.com/) - for creating and displaying the map.
-   [Bootstrap](https://getbootstrap.com/) - for styling the user interface.
-   [Proj4js](https://github.com/proj4js/proj4js) - for converting latitude and longitude to UTM coordinates.

## License

GeoCapture is licensed under the [MIT License](https://opensource.org/licenses/MIT).
