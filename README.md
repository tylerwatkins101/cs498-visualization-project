## CS 498 Data Visualization- Project Essay

By Tyler Watkins; tylerjw4
Summer 2018


View visualization by clicking here : [Final Project for CS 498 - CO2 Emissions of Vehicles Based on Rated Horsepower](https://tylerwatkins101.github.io/cs498-visualization-project/)


### About the Visualization

The chosen hybrid structure is an Interactive Slideshow. It consists of 3 slides where the reader has the ability to look at the full dataset as well as highlight data based on a categorical variable.

The visualization is based on a dataset from the Environment Protection Agency which contains horsepower, CO2 emission and vehicle type information of 4,411 vehicles manufactured in 2015.

### Scenes

There are three scenes in the narrative visualization. They follow the same template and layout for visual consistency. 
- The project title is fixed in place above the visualization container for the duration of the narrative visualization.
- The visualization container which displays the data and is consistent with height 510px, width 980px, and background color "grey" for the duration of the narrative visualization.
- The plot axes and legend are consistent for the duration of the narrative visualization. The axes are linear and extend the range of the data.
- The marks are circular and consistent in size and color for the duration of the narrative visualization.
- The scenes were designed for consistency to keep the viewer from getting disoriented through transitions.
- The order of the scenes were chosen to first highlight the overall trend of the data in scene 1, second to explore that trend in scene 2 based on the categorical variable "Vehicle Type" and see that even among different vehicles types the trend is consistent, and finally in scene 3 ask the user to reflect on this trend and perhaps consider it when making his next vehicle purchase.

### Annotations

Annotations are used to highlight a trend in the data, direct the user to further investigate the data, and ask the user to draw a conclusion from the data. The annotations use a consistent template for font size and style.
- The annotation in Scene 1 is text positioned inside the visualization container meant to highlight the primary finding of the visualization. "As horsepower increases C02 emissions increase for all vehicle types." When the user clicks the button to transition forward to Scene 2 or Scene 3 the annotation for Scene 1 is cleared.
- The annotation in Scene 2 is text positioned inside the visualization container meant to highlight the possibility of user engagement with the data. The user is invited to mouseover the data to see the trends for Cars, Trucks or SUVs independently. When the user clicks the button to navigate back to Scene 1 or forward to Scene 3 the annotation for Scene 2 is cleared.
- The annotation in Scene 3 is text positioned inside the visualization container meant to ask the user to reflect on what has been discovered in this narrative visualization and to consider this information when making his next vehicle purchase. When the user clicks the button to navigate back to Scene 1 or to Scene 2 the annotation for Scene 3 is cleared.

### Parameters

Parameters are used to engage the user in the narrative visualization and further explore the data. The parameter used in this visualization is the categorical variable "Vehicle Type". The user has the ability to examine the data of one vehicle type at a time (Car, Truck or SUV) by mousing over any data point belonging to that particular vehicle type. This allows the user to gain more information about the relationship between horsepower and CO2 output, not only as an overall trend, but based on vehicle type as well. 


### Triggers

Triggers are utilized in two ways for this visualization.

The buttons along the top of the visualization container are triggers to change scenes. The buttons are: "Viz-Scene 1", "Viz-Scene 2", "Viz-Scene-3" and "About the Visualizaton".

The user event of clicking one of these buttons changes the current state of the visualization by changing the visualization scene. Affordance is used such that the button that represents the current state of the visualization is displayed with an increased brightness. When the user mouses over the other buttons they become temporarily highlighted which indicates to the user that they may be clicked. Upon clicking a button this triggers a change to the corresponding scene being displayed.

Triggers are also utilized with the data points.

The user event of "mouse over" a data point changes the current state of the chart by applying an opacity of 0.01 to all data not part of the vehicle type that is currently moused over. The user event of "mouse off" changes the current state of the chart by returning the opacity of all data points back to 1. This capability for the user event associated with data mouse over is communicated with an annotation.


### References

Example of Interative Slideshow from NY Times used as reference:
https://archive.nytimes.com/www.nytimes.com/interactive/2010/02/02/us/politics/20100201-budget-porcupine-graphic.html

Tutorial for building a stepper page used as reference:
http://vallandingham.me/stepper_steps.html

D3 Scatter plot example used as reference:
http://bl.ocks.org/weiglemc/6185069



