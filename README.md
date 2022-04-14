# Visualization of Singapore HDB Classification and Carbon Emissions
## Note: Due to the reference to online resources, the results of this project could only be accessed through the web server, and errors will occur when downloaded and run locally. Access to results: https://skylargis.github.io/Singapore-HDB-Classification-and-Carbon-Emissions/

### Main technique：<br />
HTML, JS and CSS

### Library:<br />
JavaScript library ‘Mapbox GL JS’

### Main Function:<br />
#### · ① Filter: <br />
**Description:  <br />**
Choose the type of HDB block by sliding. Select the area by clicking. These two filters could work at the same time.<br />
**Coding ideas: <br />**
get input → conditional statements (if/else) & logical  statements(==/!=)<br />
First get the user's input, that is, where the user dragged the slider or clicked the button, and then set up a series of conditional statements containing logical  statements  to make the map change based on user's input.<br />
<br />

#### · ② Layer controller:  <br />
**Description: <br />**
Show layers/hide layers with the click of a button for a clear view of the different features.<br />
**Coding ideas: <br />**
click event → overwrite ‘visibility’ property<br />
In mapbox GL JS, the layer have a property called ‘visibility’, and all we need to do is to overwrite this property once the user's click event happens.<br />
<br />

#### · ③ Legend of carbon emissions:  <br />
**Description:  <br />**
The green and blue color represents a smaller index of carbon emissions, while the purple color represents a larger index of carbon emissions for the block.<br />
**Coding ideas:  <br />**
This is achieved by the layout and background color of 'div'.<br />


