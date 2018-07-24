## CS 498 Data Visualization- Project Essay

By Tyler Watkins; tylerjw4
Summer 2018


View visualization by clicking here : [Final Project for CS 498 - CO2 Emissions of Vehicles Based on Rated Horsepower](https://tylerwatkins101.github.io/cs498-visualization-project/)


### About the Visualization

The chosen hybrid structure is an Interactive Slideshow. It consists of 2 slides where the reader has the ability to look at the full dataset as well as highlight data based on a categorical variable.

The visualization is based on a dataset from the Environment Protection Agency which contains horsepower, CO2 emission and vehicle type information of 4,411 vehicles manufactured in 2015.

### Scenes

There are two distinct scenes in the narrative visualization. They follow the same template and layout for visual consistency. 
- The project title is fixed in place above the visualization container for the duration of the narrative visualization.
- The visualization container which displays the data and is consistent with height 510px, width 980px, and background color "grey" for the duration of the narrative visualization.
- The plot axis and legend are consistent for the duration of the narrative visualization. The axes are linear and extend the range of the data.
- The marks are circular and consistent in size and color for the duration of the narrative visualization.
- The scenes were designed for consistency to keep the viewer from getting disoriented through transitions.
- The order of the scenes were chosen to first highlight the overall trend of the data with an annotation and to then invite the user to explore the data based on a categorical variable.

### Annotations

Annotations are used to highlight data and direct the user to further investigate the data. The annotations use a consistent template for font size and style.
- The annotation in Scene 1 is text positioned above the data inside the visualization container meant to highlight the primary finding of the visualization. "As Horsepower increases C02 Emissions increase for all vehicle types." When the user clicks the button to transition to Scene 2 the annotation for Scene 1 is cleared.
- The annotation in Scene 2 is text positioned near the user interface to highlight the possibility of user engagement with the data. If the user clicks the button to navigate back to Scene 1 the annotation for Scene 2 is cleared.

### Parameters

The essay properly discusses the parameters of the narrative visualization, including describing which parameters control the current state of the narrative visualization.

Parameters are used to engage the user in the narrative visualization and further explore the data through filtering. The user has the ability to highlight the data based on vehicle type by clicking the toggle on the upper right corner of the chart. This allows the user to gain more information about the relationship between horsepower and CO2 output based on vehicle type. The user event of clicking the toggle changes the current state of the chart to highlight the data of that selected vehicle type.

### Triggers

The essay properly discusses the triggers, including what user events trigger what parameter value changes, and how the viewer is aware of available user events.

The triggers utilized are the buttons along the top of the visualization container that indicate to the user how to change scenes. 

The buttons are: "Viz - Scene 1", "Viz - Scene 2", and "About the Visualizaton".

The user event involves clicking one of these buttons.

Affordance is used such that the button that represents the current state of the visualization is displayed with an increased brightness. When the user mouses over the other buttons they become temporarily highlighted which indicates to the user that they may be clicked. 

Upon clicking a button this triggers a change to the corresponding scene being displayed.


### References

Example of Interative Slideshow from NY Times used as reference:
https://archive.nytimes.com/www.nytimes.com/interactive/2010/02/02/us/politics/20100201-budget-porcupine-graphic.html

Tutorial for building a stepper page used as reference:
http://vallandingham.me/stepper_steps.html

D3 Scatter plot example used as reference:
http://bl.ocks.org/weiglemc/6185069


