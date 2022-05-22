# UFOs

## Overview
The purpose of this project was to build a table of UFO sightings stored in a JavaScript array.  I also created filters to make this table fully dynamic, meaning that it reacts to user input, and then places the table into an HTML file for easy viewing.  The filters are the following:
* The date of the sighting
* The city of the sighting
* The state of the sighting
* The country of the sighting
* The shape of the sighting

## Results
The result of building the table is a table that populates data based on the user's input.  

### The Script
The below JavaScript code is what allows the table to filter based on the user's input.  The code may seem like a lot to take in, but it is three (3) functions.

<img width="526" alt="Screen Shot 2022-05-22 at 2 41 30 PM" src="https://user-images.githubusercontent.com/99417460/169712988-47054d9f-f13b-474b-a5a8-d5f8405d1388.png">
<img width="616" alt="Screen Shot 2022-05-22 at 2 02 17 PM" src="https://user-images.githubusercontent.com/99417460/169711605-28de6390-2717-4208-8d66-1ef4ec3ff1dc.png">
<img width="586" alt="Screen Shot 2022-05-22 at 2 02 36 PM" src="https://user-images.githubusercontent.com/99417460/169711615-a0b9ecab-0fec-4d8f-8459-08fc7d2682ff.png">

### Filters
The below photograph is a picture of the table as a user would see it when he/she first opens the webpage.  Each filter input has a place holder, which guidles the user on how to input the data that they are looking for.

<img width="332" alt="Screen Shot 2022-05-22 at 1 55 43 PM" src="https://user-images.githubusercontent.com/99417460/169711388-bd2c8130-c076-4110-9639-57142d382828.png">

### Filter By Date
In order to filter by date, all the user would need to do is follow the placeholder's guidelines of "m/dd/yyyy"
<img width="899" alt="Screen Shot 2022-05-22 at 2 05 53 PM" src="https://user-images.githubusercontent.com/99417460/169711721-4c2feb12-fdd7-44c8-9914-ad144a28c2f8.png">

As one can see, when filtering by date alone, January 4th, 2010 had eight (8) reported UFO sightings.

### Filter By City
To filter by city, one would only need to type in the city name, or add extra filters to the date, state, country, or shape.
<img width="341" alt="Screen Shot 2022-05-22 at 2 09 34 PM" src="https://user-images.githubusercontent.com/99417460/169711844-ecbca730-1872-4dcf-964f-712b318d37f5.png">

### Filter By State
To filter by state, the user needs to enter the two letter state abbreviation in lower case letters (i.e. "tn").
<img width="340" alt="Screen Shot 2022-05-22 at 2 12 59 PM" src="https://user-images.githubusercontent.com/99417460/169712035-b49e82fb-a9f4-4191-90de-fcce41132cb8.png">

The user can filter by state only, or with any of the other filters to narrow down his/her search.

### Filter by Country
To filter by country, the user needs to enter the two letter country abbreviation (i.e. "us").  However, data only has two entries for Canada, and all other entries are within the United States of America.

<img width="344" alt="Screen Shot 2022-05-22 at 2 16 50 PM" src="https://user-images.githubusercontent.com/99417460/169712191-037cc499-b980-41fa-ae65-f49559001eed.png">

The user can filter by country only, or in conjunction with any of the other filters to narrow down his/her search.

### Filter by Shape
To filter by shape, the user needs to enter the shape of the UFO sighting (i.e. "triangle").  
<img width="893" alt="Screen Shot 2022-05-22 at 2 21 10 PM" src="https://user-images.githubusercontent.com/99417460/169712471-19117045-b01a-4390-99ae-14607cdfa48d.png">

As one can see, the shape filter of "fireball" returns seven (7) entries of UFO sightings.  As previously, the Shape filter can be used by itself or in conjuction with any other table filters.

## Summary
In summary, the table creates a reactive tabel that displays the data that the user is searching for.  The user can use each filter separately, or any of the filters in conjunction with each other to narrow down what the user is searching for.

### Drawback
There are a few drawbacks with this table design, however.  Below are a couple of drawbacks that I have found:
* In order to clear the table filters, the user must manually clear each filter.  Then, in order to get the entire table to reload to the webpage, the user must refresh the webpage.
* The table does not reload the data when a filter is cleared.

### Recommendations
I would recommend the following to further develop the table and webpage:
* Update the table with a filter button.  Less technically inclined users may not realize to press "Enter" or "Return" to apply the filters.  Seeing a button to click would be beneficial for that audience.
* Update the table with a clear filter button.  A button to clear all filters and start over would be beneficial rather than having to manually clear each filter space would be beneficial and save the user's time.
* Having a method to retrieve up-to-date UFO data for a user to search.  
