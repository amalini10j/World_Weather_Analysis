# World_Weather_Analysis
Repository for world weather data analysis using python code

## Overview of World Weather data Analysis
Jack, the head of data analysis in the user interface group of a travel technology company needs help to collect and present relevant imformation to users searching for hotel/lodging through the PlanMyTrip travel website. The results data should also incorporate the weather data for the relevant cities so that the users can plan their travel based on the weather forecast. This would enable end users to plan their vacations more efficiently.  

Jack needs help to provide real-time suggestions for the end user's ideal hotels. A hotel could be termed as "ideal" for a client based on the following:

- The hotel(s) are within a given range of latitude and longitude
- The location of the hotels(s) have the right kind of weather based on the client preference

## Resources
**Data Source:** schools_complete.csv , students_complete.csv
**Software:** Python 3.8, Visual Studio Code 1.59


creating a community outreach website for middle school STEM students.

This is an exciting project. These community-focused opportunities don't come around as often as you would like, and they are a great chance to get kids involved in STEM. Additionally, you work with other tech companies in the area, each taking on one aspect of the project.

Your company is going to focus on climate change, and since you know how to use Matplotlib, you decide to create some visualizations that showcase the weather parameters you retrieved with changing latitude for the 500-plus cities from all over the world. The students will then be able to use these visualizations to explore how weather parameters change based on latitude.

Now, the cherry on top of the project: a feature on the app that allows customers to search for locations they want to travel based on their temperature preferences.

Your clients will enter their preferences. Your code will tell them where to travel. It's beautiful, simple, and just needs a few more lines of code to actually work.

## School District Data Analysis Results

**How is the district summary affected?**

The district summary of the original dataset is as follows:
![Original](/Images/DistrictSummary_Original.png)

The district summary of the dataset after replacement for Thomas School data by NaN is as follows:
![Modified](/Images/DistrictSummary_AfterReplacement.png)

Except for the % Passing Reading score all other scores reduced in the summary calculated after data replacement for Thomas School

**How is the school summary affected?**
The school summary of the original dataset is as follows:
![Original_School_Summary](/Images/SchoolSummary_Original.png)

The school summary of the modified dataset is as follows:
![Modified_School_Summary](/Images/SchoolSummary_AfterReplacement.png)

The Average Math score and Average Reading score came down marginally for Thomas school but the % Passing Score for Math, reading and Overall came down significantly

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Refer to the images in the point above. The Average Math score and Average Reading score came down marginally for Thomas school but the % Passing Score for Math, reading and Overall came down significantly from ~90% to ~65%

****How does replacing the ninth-grade scores affect the following:**
**Math and reading scores by grade****
The math and reading scores for 9th graders for Thomas High school is NaN. Other data  remains the same. Refer to the screen shots below. The first one is the result with the replaced dataset and the second one is the result with the original dataset.

Reading scores based on the replaced dataset:

![Replaced_Reading](/Images/ReadingScore_Replaced.png)

Math scores based on the replaced dataset:

![Replaced_Math](/Images/MathScore_Replaced.png)

Reading scores based on the original dataset:

![Original_Reading](/Images/ReadingScore_Original.png)

Math scores based on the original dataset:

![Original_Math](/Images/MathScore_Original.png)

**Scores by school spending**
Refer to screen shots below:

The % Passing reading and % Overall Passing was lower in the replaced dataset for the spending range of 630 - 644 USD

Scores by School spending based on original dataset:

![Original_Scores](/Images/Score_BySchoolSpending_Original.png)

Scores by School spending based on replaced dataset:

![Replaced_Scores](/Images/Score_BySchoolSpending_Replaced.png)

**Scores by school size**

The % Passing reading and % Overall Passing was lower in the replaced dataset for the medium size school (1000 to 2000 students)

Scores by School size based on original dataset:

![Original_Scores](/Images/Score_BySize_Original.png)

Scores by School spending based on replaced dataset:

![Replaced_Scores](/Images/Score_BySize_Replaced.png)

**Scores by school type**

The % Passing reading and % Overall Passing was lower in the replaced dataset for the Charter schools and remained unchanged for district schools

Scores by School type based on original dataset:

![Original_Scores](/Images/Score_ByType_Original.png)

Scores by School type based on replaced dataset:

![Replaced_Scores](/Images/Score_ByType_Replaced.png)


## School Data Analysis Summary
The four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are as follows:

1. The % Passing Score for reading and % Overall Passing score got reduced for the Charter schools
2. The % Passing Score for reading and % Overall Passing score got reduced for the medium sized schools (having 1000 to 2000 students)
3. % Passing Score for reading and % Overall Passing score got reduced for the schools having spending of 630 to 644 USD per student
4. The Math and Reading scores for Thomas High School got reduced


