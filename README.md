# UFOs
 
## Overview 
Dana has always been interested in UFO's.  She has been give a large data file on various UFO sightings from all over the world and would like to allow users to have the ability to read her article as well as search the data she has collected for their own analysis.  Dana had to build a table using data stored in a JavaScript array and filters to make this table fully dynamic, allowing it to react to user input, and then place the table into an HTML file for easy viewing.  Dana customized her webpage using Bootstrap, and equiped her table with several fully functional filters that will allow users to interact with the visualizations.

## Results

Because a webpage was ultimatly used as the interface between search criteria, display, and user interface, JavaScript files were used to sort through the data files and return the necessary results.  Dana used HTML as a user-friendly interace between the data, and the search functionality, and the returned results.
When the webpage it first accessed it displays the list all of the data in the data.js file.  
At initial glance this is good, showing the user there is plenty of data to sort through.  Not only does the dataset contain information on when and where the sighting was, but also a small description of the sighting, including shape, duration, and description of the event.
![Fig 1 - Initial Open](https://github.com/ASCHEET/UFOs/blob/main/static/images/Fig%201.png?raw=true)
As the user needs or wants to look up something specific, installed are several filter buttons that will filter the data based on Date, City, State, Country, or even shape of the UFO sighted.  For example, below is a list of the results for California.
![Fig 2 - Cali results](https://github.com/ASCHEET/UFOs/blob/main/static/images/Fig%202.png?raw=true)

## Summary
One current drawback seems to the be dataset itself.  Many of the dates seem inconsistant for an accurate database.  Possible data-refining might be needed for accuracy. 
For the next iteration of the HTML, it would be good to allow users to enter a keyword or phrase that would sort through the "Comments" to determine if similar patterns are seen at different locations on the globe (e.g. 3 Red lights).  Another improvement would be to add a google API location on the returned results to see if multiple entries could be referring to the same sighting, so multiple entries of the same sighting could be refined.









