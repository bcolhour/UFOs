# UFOs
## Project Overview
In this challenge, we are assiting in building a webpage utilizing javascript to organize UFO data in a table that can be filtered by multiple criteria. JavaScript is a good choice for this project as it is a well established coding languange designed to enhance front end user experience, improving functionality and creating dynamic webpages. 

We will be using a JavaScript array, index.html (utilizing css styles) and our data to produce a dynamic webpage featuring a table of UFO Sighting information. This information will be able to be filtered multiple ways simultaneously. 

## Results
A basic, user friendly page was created with css styling that provides UFO sighting information in a table format. This information can be filtered by date, city, state, country or shape. The table is dynamically filtered as data is entered. and can be very precise using all filters, or much more broad using fewer filters as desired. 

![UFOpage](https://user-images.githubusercontent.com/114044192/210023975-6c46b804-1dbf-4721-8f59-da02ab527c43.png)

#### City Filter
![cityFilter](https://user-images.githubusercontent.com/114044192/210023977-e0201d1b-3031-45ed-9b59-b379ee47b504.png)

#### Date Filter
![dateFilter](https://user-images.githubusercontent.com/114044192/210023978-92b84274-5144-45b3-89a5-5e7f66d89763.png)

#### Shape Filter
![shapeFilter](https://user-images.githubusercontent.com/114044192/210023980-4e2db450-2ba5-41ea-a439-f82ec1ee709b.png)

#### State Filter
![stateFilter](https://user-images.githubusercontent.com/114044192/210023981-682379d3-26d9-4bc0-8816-e5d6eff7f309.png)

#### multi Filter
![multiFilter](https://user-images.githubusercontent.com/114044192/210023979-1a2597aa-c800-42a0-a4b3-3c7e5de87a3a.png)

## Summary
Our webpage is visually appealing, has basic functionality, and allows multiple filtering options. However, there are several disadvantages to the current layout.

### Disadvantages
- Case sensitive search
- no filter reset
- user needs to know exactly what they are looking for
- user can not filter by multiple criteria in same search (such as a date range, 2 states, 3 shapes, etc.)

### Recommendations to address disadvantages:
- make search criteria based typed text (in any part of result) not case sensitive 
- add a clear filters button so that they do not have to be reset individually
- provide searchable (wth typed text) drop down of available choices from table for each criteria.
- allow a date range and allow multiple selections on each criteria. 

### Additional recommendations for further development

1. Dana should implement the above recommendations to improve functionality. 
2. Add a dynamic graphics generator that can visually show results (i.e. percentage of sighting for each shape, city, etc.)
3. Add a map graphic to visually dipict locations of sightings. 
