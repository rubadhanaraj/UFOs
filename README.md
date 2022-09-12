# UFOs
## Overview of Project:
The purpose of this project is to create a table to organize UFO data that is stored as a JavaScript array, or list and to filter data based on certain criteria using JavaScript as the primary coding language. In this project, 
* The strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+ were explained
* JavaScript syntax and ideal use cases were described
* Built and deployed JavaScript functions, including built-in functions.
* Converted JavaScript functions to arrow functions.
* Built and deployed forEach (JavaScript for loop).
* Created a table and dynamically filtered the table using JavaScript and HTML.

## Results:
The challenge in this module was to add filters in the table created with UFO data by allowing users to filter for multiple criteria at the same time. In addition to the date filter, filters for the city, state, country, and shape were added.

![image](https://user-images.githubusercontent.com/108298416/189553723-f448bfa2-1ac7-4873-9fbf-a2f2e553f13d.png)

The user can filter the UFO sightings table either by filtering one criteria or by filtering multiple criteria at the same time. 
1. The results when filtering the table by state "ca" and date "1/5/2010" shows just the filtered row.

![image](https://user-images.githubusercontent.com/108298416/189553944-21bf3d06-6885-4d90-9b91-752869c3cdb6.png)

2. The results with country "us" and shape "triangle" as the filters.

![image](https://user-images.githubusercontent.com/108298416/189554039-78674162-8ff2-4a11-ac87-16c93492d41c.png)

## Summary
### Drawbacks
1. The date filter could have a range (from and to dates) instead of taking a single value, so that user can get results of UFO sightings for a date range. 

![image](https://user-images.githubusercontent.com/108298416/189567297-8c577122-0cf5-49f0-9e4b-2106746e42d9.png)

2. The user needs to remember the filter values so that they can enter and search for the right information. 

### Recommendation
1. The filters can be assigned with a pre-populated values in a drop down menu so that the user can select the options from drop down menu.
2. The number of UFO table values filtered by user input can be shown on top of the table, to make the filters user friendly.
3. A reset button can be assigned below the filter buttons, instead of clearing the previous user inputs, by clicking ufo sightings in the top of the web page.

