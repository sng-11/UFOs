# UFO Sightings

## Overview of Project
The purpose of this coding project is to create a dynamic HTML webpage that allows users to view data on UFO sightings. Using Javascript, CSS, and Bootstrap, this HTML webpage is designed to take raw UFO sightings data and put them in a dynamic table. The purpose of this page is to also allow users to filter the displayed data based on parameters they are interested in, such as sightings on a certain date, in a certain country etc. The coding used in this project allows for this dynamic interface to be created.

## Results

1. The table can be filtered based on date of interest, e.g. entering 1/7/2010 in the date input box:

<img width="1426" alt="Screen Shot 2021-09-12 at 10 04 56 PM" src="https://user-images.githubusercontent.com/84816495/133013436-ec02a470-ac1c-48f5-8999-426bf635364c.png">

2. It can also be filtered to show sightings in a specific city, e.g. entering willow in the city input box:

<img width="1430" alt="Screen Shot 2021-09-12 at 10 06 53 PM" src="https://user-images.githubusercontent.com/84816495/133013572-2668f0e6-b49d-4447-9792-2be764ee7807.png">

3. It can also be filtered to show sightings in a specific country, e.g. entering canada in the country input box:

<img width="1429" alt="Screen Shot 2021-09-12 at 10 07 52 PM" src="https://user-images.githubusercontent.com/84816495/133013637-9b4cdf05-ce34-4971-b98a-575e2ea9cdd7.png">

4. Finally, the table can also filter based on shape of the seen UFO, e.g. entering fireball in the shape input box:

<img width="1432" alt="Screen Shot 2021-09-12 at 10 08 44 PM" src="https://user-images.githubusercontent.com/84816495/133013699-4d5dd631-60db-45c8-92d8-13db971236ae.png">


## Summary
A drawback of this current design of the webpage is that it is necessary for the exact same text entered in the input boxes in order to filter appropriately. For example, while "benton" as a city will yield the necessary row, inputting "Benton" will not. 

### Future Developments for this Webpage
- Building off of the aforementioned drawback, it would be useful to take into account different inputs that do mean the intended city/state/country. For example, appropriate filtering should still occur if the "United States" in addition to "us". 
- An interesting new function to include would be to allow for sorting based on date and/or duration. For example, dates can be sorted from "Most Recent" to "Least Recent", while durations can be from "Longest" to "Shortest". This allows for users to interpret the data in a different way.
