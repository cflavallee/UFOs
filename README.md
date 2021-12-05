# UFOs

## Overview
The purpose of this project is to create a webpage related to UFO sightings.  The webpage allows users to filter the data table in order to get specific sightings based on user input.  The user can filter through Date, City, State, Country, and/or Shape.

## Results
To begin filtering the table, one needs to enter an input in one or more of the filter fields.  Then, by hitting the enter key on one's keyboard or clicking outside of the input fields, the table will reload and only the filtered data will show on the table (if any exists with the specified criteria).  The image below shows the table being filtered when "El Cajon" is entered in the City input field.

![filter example 1](https://github.com/cflavallee/UFOs/blob/main/filter%20image1.png)

Below is a filtered search using a Date of "1/4/2010" and a Shape of "Light".

![filter example 2](https://github.com/cflavallee/UFOs/blob/main/filter%20image3.PNG)


Once a search is complete, the user can clear the search fields and reset the table back to the full dataset.  The image below shows the table reseting after the "El Cajon" search above was done. 

![clear example](https://github.com/cflavallee/UFOs/blob/main/filter%20image2.PNG)

## Summary
One drawback of the current UFO site design is that the entire table is present when the page loads or when a search is cleared.  This makes the site look a bit cluttered and would look and feel even worse with a larger dataset.  Updating the code to hide or truncate the table until filtering is complete would improve the look and user-friendliness of the site.  

Another drawback is how specific the search currently needs to be in order to get results.  Adjusting the code so that the search does things like ingoring case or allowing users to enter part of a word or date to get search results would improve how the table interacts with the filters. 

