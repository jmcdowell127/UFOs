# UFO Sightings

## Overview
In this project I have created a dynamic webpage by mainly using JavaScript and HTML for coding purposes and then CSS and Bootstrap for styling and formatting. This webpage provides an in-depth analysis of alleged UFO sightings during a 14 day span from January 1, 2010 to January 13, 2010. I have created a table from a provided data JavaScript file that includes up to 111 claimed UFO sightings. I have placed this data in an easy to follow table, which changes depending on the user-entered filters. For easy navigation and filtering purposes I added multiple filter search options (date, city, state, and shape) so that the user can access the data however they please. 

## Results
This webpage is both easy to use and navigate. The user can either enter 1 of the 5 filters or use a combination of filters to retrieve even more specific results. Below are examples of how to use the search criteria to access desired results.

### Filtered by Date:
![date_filter1](https://user-images.githubusercontent.com/85372441/131564714-5f9b9e28-1b1e-4525-955b-fbc51dae124f.png)![date_filter13](https://user-images.githubusercontent.com/85372441/131564733-ed91b122-50d8-421e-a169-084d072f50a8.png)

### Filtered by Country:
![country](https://user-images.githubusercontent.com/85372441/131565170-4471c949-4d58-45b8-83cb-44afe371d033.png)

### Filtered by State and Shape:
![stateShape_filter](https://user-images.githubusercontent.com/85372441/131565281-4f5e5c10-af62-4cf9-9ac0-615b6cde0d08.png)

### Filtered by Date, State, and Shape:
![filtered3](https://user-images.githubusercontent.com/85372441/131565874-2474dd3b-55d8-4920-87ca-6afde1d4cd9a.png)

## Summary
The webpage is dynamic and works well. However, there are some drawbacks to this design as listed below.
* The user does not know that the provided data is only between January 1, 2010 and January 13, 2010 when accessing the webpage. The filter search for date then becomes tedious on the user to find dates that they care to see.
* There is only one other country, Canada (ca), provided in this table. Random users will not know this and will also have to know the Canada's country abbreviation of 'ca'. 
* The user is not aware of the available shapes to filter by, leading them to find out through trial and error.

I would recommend the following adjustments/additions for further development:
* Include drop-down lists on all 5 filter options in place of the input fields. This way the user can easily see/access the specific options they prefer.
* Gather and include more data for ranging dates outside of January 1-13, 2010 as well as from other countries outside of the US.
* If data is gathered from more countries, edit the current 'Enter State' filter to 'Enter State/Province'
* Add a 'Choose Language' filter for those users who do not speak english.

