# Rutgers-UFOs

## Overview of Project

The purpose of this project is to add a number of filters to the UFO sightings data table. As values are entered into the search forms, the table data will 
update and filter based on these values. The project utilizes CSS and Javascript to work with the HTML and produce a dynamic webpage.

## Results

* Originally the search was conducted by adding a date and clicking the filter button to create a filtered table with data from the selected date. Now
the filter criteria for the table are determined by entering values into each of the filter forms.
* As the values are entered into the forms the table is updated to match these criteria.
* The values entered must be an exact match to the table values for the Javascript to recognize a match to the filter criteria. 
* Below is a filtered table of the sightings where the State is 'ca', the country is 'us', the date is '1/1/2010' and the shape is 'light'. 

![Filtered Search](/static/images/shapeSearch2.png "Filtered Search")

## Summary

### Drawback
A drawback of this design for the filter criteria is that each value entered into the forms must be an exact match with the table values in order to filter
the table data properly.

### Recommendations
Two additional features for the filter would be a dropdown menu to show the different value options available for each filter and a sorting option for each 
column in the table.
