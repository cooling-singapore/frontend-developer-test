## Cooling Singapore 2.0

### Frontend Software Engineer Test

Develop a web application to align a 3D model with a color map. The application will contain two parts. Part one is A data visualization component shows a 3D model and a color map. Part two is a control panel allows users to input xyz coordinates for the 3D model and the color map. Each time when a user input one coordinate, the visualization component should update the position of the model or the heatmap immediately. Users can keep editing the position of the two elements until they aligned with each other.

Please see the following image as the targetted UI layout. 

![alt text](image/uiSketch.png "Title")

Note:
* Make use of React to create the web application, all elements should be contained in React components
* Make use of [Arcgis](https://developers.arcgis.com/javascript/latest/) javascript library to visualize the 3D model and the color map. The color map should be created from the given csv data sheet called color map. In the csv file, each cell is marked by a number between 0 to 3. You are free to assign colour to each number to generate the color map.
* 3D model and the data is located in the ./data folder. Please make sure the application access the data directly from github. DO NOT load the data from local folder.
* To simplify the process, only position alignment is required, but it will be nice to have a rotation input panel to perporly align rotation too. 
* You may ask questions/seek clarification about the exercise over email if required
