# NYC Citibike Challenge
## Overview and Deliverables
Citibike rideshare data for August 2019 in New York City were analyzed in order to determine trends in bike usage across the city.  These findings will provide information for investors who may wish to fund a similar bikeshare program in Des Moines, Iowa. In addition to visualizations created for number of rides, customer type, peak hours, top starting and ending locations, gender breakdown, average trip duration, bike repairs, and bike utilization, the following deliverables were requested:
  - Checkout times for users
  - Checkout times by gender
  - Number of bike trips per weekday per hour
  - Number of bike trips by gender (weekday per hour)
  - User type (customer vs. subscriber) trips by gender by weekday

## Resources
- Data Source: 201908-citibike-tripdata.csv (downloaded from https://s3.amazonaws.com/tripdata/index.html on 18 March 2022)
- Software: Tableau Desktop Public Edition v. 2021.4.4; Jupyter Notebook v. 6.4.6

Tableau was used to create all charts and graphs.

Jupyter notebook was used to convert data from an integer to a datetime datatype in the "tripduration" column from the original .csv spreadsheet.  All other column data remained the same.  The new spreadsheet, which contained the datetime datatype for "tripduration," was named "citibike-trips.csv" and was used in these analyses.

## Results
### Tableau NYC Bikeshare Story
Link to the NYC Bikeshare Story in the NYC_rideshare_Challenge workbook.  Read through the story created with the five deliverable charts and graphs and two additional original charts.
- [link to dashboard] (https://public.tableau.com/app/profile/christy2982/viz/NYC_rideshare_Challenge/Story--NYCBikeshareStory)

### Explanation of the Deliverables
 1) Gender breakdown:
 
![Gender Breakdown](https://user-images.githubusercontent.com/95387273/159580834-1355d2b0-f059-439a-aee4-c4b392b37bbd.png)

- There are a total of 2,344,224 individuals riding bikes in New York City.  65% are men, 25% are women, and 10% are 'unknown'.
- [Link to Gender Breakdown in Tableau Public] (https://public.tableau.com/app/profile/christy2982/viz/GenderBreakdown_16479905433480/GenderBreakdown?publish=yes)



2) Checkout times for users:

![Checkout Times for Users](https://user-images.githubusercontent.com/95387273/159582769-b02e9fd4-c722-44b5-b1f1-cdcca0bca428.png)

- Most users ride bikes about 10 min.



3) Checkout times by gender:

![Checkout Times by Gender](https://user-images.githubusercontent.com/95387273/159583277-b59b4ffc-c55e-4ba7-977e-72dea849f0d7.png)

 - Women and men ride for about the same length of time (10 min.), with men riding slightly longer than women.  Those in the "unknown" category ride anywhere from 10 to 30 min.


4) August Peak hours:

![August Peak Hours](https://user-images.githubusercontent.com/95387273/159583930-35ad09d8-3fca-46c0-873b-1d48f2541c3b.png)

 - Bike usage is greatest at morning (8-9 am) and evening (4-7 pm) rush hours.
 - [Link to August Peak Hours in Tableau Public] (https://public.tableau.com/app/profile/christy2982/viz/AugustPeakHours_16479903519590/AugustPeakHours?publish=yes)


5) Number of bike trips by weekday per hour:

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/95387273/159585060-89a4c93b-2d64-46ff-addf-2f03a76e7096.png)

- Bike use corresponds to morning and evening rush hours for the work week from Monday through Friday.  Bike use during the weekend is distributed throughout the daytime on Saturday and Sunday with the greatest usage during the late morning on Saturday for all users.


6)  Number of bike trips by gender (weekday per hour):

![Trips by Gender wkdy per hr](https://user-images.githubusercontent.com/95387273/159585822-aa4b195b-5fc3-47d2-a602-d76c664f1b85.png)

- Both men and women ride bikes primarily at morning and evening rush hour times during the work week from Monday through Friday, and late in the morning on Saturday.  Those in the "Unknown" category are most likely tourists who ride through the city during daylight hours on Saturday and Sunday.


7) User type (customer vs. subscriber) trips by gender by weekday:

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/95387273/159586543-587f1ca3-520e-407c-9f9e-35805b69ab21.png)

- Both male and female *subscribers* showed similar usage throughout the week, with the highest use on Thursday and Friday.  Both male and female *customers* had the greatest bike use on the weekend, and are more likely tourists.  Those in the "unknown" category are more likely to be customers who have the greatest use on the weeend. "Unknown" subscribers show an even distribution of use across all weekdays.





## Summary
