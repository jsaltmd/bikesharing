# Bikesharing

### Overview of the statistical analysis:

In this module challenge additional bike trip analysis through data visualizations were generated to convince investors that a bike-sharing program in Des Moines is a solid business proposal. 

Data visualizations for the Trip Analysis generated are as follows:

- The length of time that bikes are checked out for all riders and genders.

- The number of bike trips for all riders and genders for each hour of each day of the week.

- The number of bike trips for each type of user and gender for each day of the week.

The deliverables for this Challenge are as follows:

- Deliverable 1: Change Trip Duration to a Datetime Format

- Deliverable 2: Create Visualizations for the Trip Analysis

- Deliverable 3: Create a Story and Report for the Final Presentation


### Results:

Deliverable 1: Change Trip Duration to a Datetime Format

- Pandas was used to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes.

Before: unconverted csv file.

![](./pictures/pic.png)

After: converted csv file.

code: df["tripduration"] = pd.to_datetime(df.tripduration,unit="m")

![](./pictures/pic2.png)






There are at least seven visualizations for the NYC Citibike analysis (7 pt)
There is a description of the results for each visualization (7 pt)

[Link to Tableau Story with Dashboard](https://public.tableau.com/views/NYCCitibikeAnalysisStory/NYCCitibikeAnalysisStory?:language=en&:display_count=y&:origin=viz_share_link)

### Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)
