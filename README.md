## Cooling Singapore 2.0

### Frontend Developer Test
You are tasked to develop a web application to align a 3D model with a colored map. The application should contain two parts. Part 1 involves a data visualisation component that displays a 3D model and a map. Part 2 is concerned with a control panel that allows its users to input `x`, `y`, `z` coordinates for the 3D model and the map. The visualisation component should automatically update the position of the model or the map every time a user changes any on of the coordinates. Users should be able to keep modifying the position of the two elements until they are aligned with each other.

The following images should give you an idea what we are looking for:
![alt text](image/uiSketch.png "Title")

### Getting started
Please create a new repository using your own GitHub account (do *not* fork this repository). Use the new repository to build your solution. We are looking to assess for you ability to write high quality code. You should focus on the software design and functionality rather than the UI design. Familarity with GitHub is also expected.

Note:
* Make use of React to create the web application. All elements should be contained in React components.
* Make use of the [ArcGIS](https://developers.arcgis.com/javascript/latest/) javascript library to visualise the 3D model and the map. The map should be created from the given CSV data sheet called `map.csv`. In the CSV file, each cell is marked by a number between 0 to 3. You are free to assign colors to each number to generate the map.
* The 3D model and the CSV file are both located in the `./data` folder of this repository. Please make sure your application accesses the data directly from here. Do not load the data from a local folder.
* To simplify the process, only position alignment is required but it would be be nice to have a input panel for rotation as well.
* If you have any questions, please seek clarification via email (cong.ye@sec.ethz.ch).


### When done
Please share your repository with us so we can have a look. If we think you have potential, we will invite you for an interview to give you an opportunity to explain your solution and also to learn more about the project and the role.
