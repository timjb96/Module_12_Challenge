# Module_12_Challenge

## Overview
For this challenge, we improved the website we made for Dana to better showcase the UFO Data. To do this, we added several more filters.
These were city, state, and shape of the sighting.

## Results
To do this, we first had to add the new items to the index.html file, using the following 'li' tags. 

![Screen Shot 2022-12-01 at 7 46 47 PM](https://user-images.githubusercontent.com/112847821/205210510-4753ba37-bcef-4536-947c-c53555f7ac8b.png)

This left us with the following set of filter options:

![Screen Shot 2022-12-01 at 7 48 32 PM](https://user-images.githubusercontent.com/112847821/205210705-c6ef8d7d-bdfe-4126-8d6a-7fc7f11a2605.png)

To add functionality, we utilized the following script in the app.js file:

![Screen Shot 2022-12-01 at 7 49 20 PM](https://user-images.githubusercontent.com/112847821/205210785-7d4ec75d-ce7b-4294-b571-60c1e6003ca2.png)

By creating the filters variable, we are able to keep track of all filters entered in the filter search bars, and use them to rebuild our table with the following function that applies the filters variable to the table itself, and displays the proper content. 

![Screen Shot 2022-12-01 at 7 50 41 PM](https://user-images.githubusercontent.com/112847821/205210939-081eb0a7-ae02-4d70-bb57-2adf1b751487.png)

## Summary
This webpage is very useful, and pretty straightforward. However, there are some drawbacks. 
The biggest drawback is that it will only respond to very specific filters- the filter input must exactly match the information in data.js. 
Therefore, if a user typed 'Benton' instead of 'benton', the site will return no results. Since many individuals will automatically capitalize the first letter of a city (and the abbreviation for a state for that matter), this will render it unusable for a majority of people without further instruction. 
The two main changes that could be made would be to first make the filter input not case sensitive. Additionally, further filters could be entered for duration and comments, as these also provide useful information that a user may want to reference. 
