# bikesharing

## Overview 
The purpose of this analysis is to convince investors and solidify the proposal that a bike-sharing program in Des Moines is a great inverstement and business venture. For this analysis, Pandas will be utilized to change the "tripduration" column from an integer to a datetime datatype and then this converted datatype will be used to create a set of visualizations to:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

These new visualizations will be added to the previously created visualizations for a final presentation and analysis to pitch to investors.

## Resources
### Data Source 
- [?](?) 

### Software
- Tableau Public 2022.2
- Python 3.7.6
- Conda 4.13.0
- Jupyter Notebook
- Dependencies:
  - Python Pandas Library

## Results
### Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00) and export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

1. The data in the "tripduration" column is converted to a datetime datatype and has the correct time format:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193474116-24f5f00e-7ca1-4d7f-b070-ebe7cc90e34f.png)

2. The DataFrame is exported as a new file without the index column:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193474090-6a11e9c8-278d-4017-af10-8688eeedaf6e.png)

### Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:
  - How long bikes are checked out for all riders and genders.
  - How many trips are taken by the hour for each day of the week, for all riders and genders.
  - A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

1. There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193476990-3d3096de-cc41-4f5e-b6a3-489be9e860ae.png)

2. There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender: 
<br /> ![image](https://user-images.githubusercontent.com/108038989/193476976-9ef60378-2a28-4e3f-a81d-f34f84e836fb.png)

3. A heatmap is created showing the number of bike trips for each hour of each day of the week:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193476967-fd6a8bc6-507c-440d-837a-2e55ebb8af7b.png)

4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193476945-1ec7eac2-78a3-4755-9f79-21fa55aec342.png)

5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender:
<br /> ![image](https://user-images.githubusercontent.com/108038989/193476898-84974389-2707-40fd-a381-ecb65f5e1eab.png)

### Deliverable 3: Create a Story and Report for the Final Presentation
Create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis performed in the module and in Deliverable 2.

[link to dashboard](LINK)

## Summary 
There is a high-level summary of the results and two additional visualizations are suggested for future analysis
