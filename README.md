# Module 11 : UFO Data Challenge

### Overview of the Analysis:
The index.html webpage developed uses Javascript to iterate through an array of objects and present users with a final table filtered based on their   selected criteria. In this particular case, users are provided a webpage that allows access to a data repository of UFO sightings. Based on date, city, state, country and UFO shape criteria, users can filter the available data as they choose. 
  
  
### Results:

The result of this webpage/Javascript build is an instantly responsive, filtered table that uses a 'changed element' listener to dynamic filter the table as filters are applied real-time. As you can see below, the screenshot shows the table results when filtered on the elements city: e; cajon, state : ca, country: us, and shape: triangle. Should a user wish to see another filter, simply select the filter box and type the requested filter id. Upon text change, the table is filtered accordingly. If any filter is left blank, that filterID in the filtered objects is deleted and the filter is not applied on this column. 

**Fig 1: Example of Filtered Data**
![Webage_Image](https://github.com/dpTuttle/UFOs/blob/main/static/images/webpage_screenshot.png)

### Summary:
In summary, this table provides a limited filtered view of the data. Although the table is dynamic and allows users to select for certain criteria, it is not dynamic enough to process non-absolute values. Should a user be interested in a particular data range or number of cities at once, this webpage cannot deliver the results. 

One such improvement to the webpage may be allowing the date field to be dynamic--possibly putting in two fields that allow users to type in a range of dates and the table filter the data for event dates in the same period. Another change could be made to the city, state, country, and shape fields to allow a drop down that is populated by all available values in each column. The Javascript code can access the table, filter the unique values, append those to an object, and then use that object to populate a multiple choice dropdown. Users can select one or many criteria to complete their filter. 
