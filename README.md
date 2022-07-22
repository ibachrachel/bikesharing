# Module 14 Challenge: Bikesharing

[Click here to view the Tableau story](https://public.tableau.com/shared/KBGTXPFMP?:display_count=n&:origin=viz_share_link)


## Overview

*Background*

On trips to large cities and landmarks, a great way to see the sights and interact with the people is to use a bike to get around. CitiBike in New York is extremely popular and a couple of entrepreneurs would like to analyze why it is so success in New York. They intend to implent a similar program in Des Moines, Iowa and must be able to understand the components. This will help them institute a successful program in their home city. 

*Purpose*

Funding the program will be the next step in setting up the bike share, so it's important to create a convincing argument to pitch. To convince investors that a bike-sharing program in Des Moines is a solid business proposal, a bike trip analysis will be shown to  the key stakeholders. From the CitiBike Data, the "tripduration" column will need to be changed from an integer to a datetime datatype. Then, using the converted datatype, visualizations will be created to show the following: 

- the length of time that bikes are checked out for all riders and genders
- the number of bike trips for all riders and genders for each hour of each day of the week
- the number of bike trips for each type of user and gender for each day of the week.

## Results

*Visualizations*

![Most Common Rental Times](https://user-images.githubusercontent.com/102566199/180356916-04985bcb-a15f-4d47-8888-0fe20ec40846.png)

### Users bike checkout times displayed through a line chart to demonstrate the most common rental times.

![User Rental Times by Gender](https://user-images.githubusercontent.com/102566199/180357258-ae702a26-5aac-4580-93ab-5358dcf0405f.png)

### Users bike checkout times displayed through a line chart, which demonstrates usage by gender.

![Trips by Users per Week per Hour](https://user-images.githubusercontent.com/102566199/180357434-88a3051b-f5dc-4d9e-a7e8-7b6f4dcf258b.png)

### Trips Made by Users during the Week (per the hour) displayed through a heat map.

![Trips per Week per Hour by Gender](https://user-images.githubusercontent.com/102566199/180357585-ffe3995b-dbd1-4067-aa7d-ed4211a4e30b.png)

### Trips Made by Users during the Week, per Hours by Gender, displayed through a heatmap.

![Trips by Gender by Weekday](https://user-images.githubusercontent.com/102566199/180357711-d1c7e78a-f364-49b9-8267-938225a68fcf.png)

### User Trips by Gender by Weekday

![Customer Pie Chart](https://user-images.githubusercontent.com/102566199/180357802-3204ccb8-2115-4fa3-b47d-b6b76146dc79.png)

### Count of subscribers vs. customers shown via a pie chart.

![Starting Locations](https://user-images.githubusercontent.com/102566199/180357889-5e2c277f-d9ce-41e9-bc40-2de44b3f2b9f.png)

### A map of the starting locations shows the most prominant locations used by customers.  

## Summary

Based on the visualizations of the data, there are many takeaways that can lead to a final conclusion on the Bike Share project. The first visualizations show that the main use of the New York CitiBikes is as transportation to work for local commuters. The majority of rides are around 5 minutes and peak around commuting times, both 8 am and 6 pm. This means that the bikes serve as a means of transportation to work more than they are used by tourists of the city. The next couple of visualizations highlight that the largest population using the bikes are men and are subscribers to the program, rather than customers. Although the CitiBike data did show that non-subscribers used the bikes are longer than 5 minutes, perhaps because tourists are using it to go to less predictable locations. 

*Additional Visualizations*

These visualizations help understand that for something like this to work in a location other than New York, it would have to be dramatically rearranged to allow for it to be useable for a more sprawling landscrape, such as Iowa. For this project to truly know that this will work, it would be beneficial to draw more conclusions based on specific criteria that are different between New York and Iowa. A visualization that highlighted the differences in usage based on weather conditions would be beneficial, considering that New York is a coastal location and Iowa is landlocked. Another visualization that would be helpful to look at would be a tracking of the starting and ending locations of non-subscribers. This would help to understand where the tourists are focused and how they are influencing the data.
