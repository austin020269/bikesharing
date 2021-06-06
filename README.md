# bikesharing
UT Bootcamp Module 14 Challenge

## Project Overview
To research the idea of opening a bicycle sharing program in the Des Moines, Iowa area based on data and analysis from the New York City bicycle sharing program.

## Resources
Data provided for the project included August 2019 Citi Bike data (201908-citibike-tripdata.csv) as well as using the following software and applications:
- Personal Tableau Public account
- Pandas
- Conda
- Personal Github account

## Analysis and Workflow - 
Pandas was used to display and clean the data that was then exported to a new .csv file and later used in Tableau to create visualizations for the Challenge.

Deliverable 1: 
1. Create a DataFrame from the 201908-citibike-tripdata.csv file.
2. Check the datatypes of each column in the DataFrame.
3. Convert the "tripduration" column to a datetime datatype by passing the DataFrame column and the units inside the to_datetime() function.
4. Check the datatypes of the DataFrame.
5. Export the DataFrame as a new CSV file without the index column and use this new CSV file for Deliverable 2.

![alt text](https://github.com/austin020269/biksharing/blob/main/CH1_Deli1.PNG)
![alt text](https://github.com/austin020269/biksharing/blob/main/CH1_Deli1_2.PNG)

Deliverable 2:
1. There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_1.PNG)

2. There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_2.PNG)

3. A heatmap is created showing the number of bike trips for each hour of each day of the week.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_3.PNG)

4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_4.PNG)

5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_5.PNG)
