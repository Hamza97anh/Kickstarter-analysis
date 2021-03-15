# An Analysis of Kickstarter Campaigns. 
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
  In the Kickstarter Excel sheets. We find  a collection of data gathered from various kickstart fundraisers outlining key data sets that help determine what makes a successful kickstarter campaign. In this Reposstory. You will find a collection of charts extrapulated from the Kickstarter sheets to help outline key factors that display what makes a good Kickstarter campaign. 
### Purpose
  Louise's play "Fever" came close to its fundraising goal in a short amount of time. Now she wants to know how different campaigns fared in relation to their launch dates and their funding goals. By using data from the Kickstarter sheets. I display a series of charts that show the outcome of plays in relation to the launch date and a chart the displays the outcome of plays in relations to their respective goals. 
## Analysis and Challenges
  In the intial stages. We first sifted through the data and made it more organized by color coding some colums to make them easier to visualize. We took some data that was harder to read and converted to a format that was easy to comprehend such as dates. We divided the types of events to Parent Catagories and Subcatagories to make it easier to filter out our desired data. 

### Analysis of Outcomes Based on Launch Date
  For the Outomes Based on Launch Date we created a new column for year using code "=Year()". This was necassary for out next step where we creat a pivot table to that we can then use to make a chart. The "Years" Column is used to add filters if needed for our chart. In our Pivot table we used the "Parent_Catagory" and "Years" for the filters. "Outcomes" for the Columns, "Date_Created_Conversion" for the rows and the "Count_of_Outcomes" for the values. From this we filtered for "theater" in the "Parent_Category" filter which we then made a line chart from.
![Outcomes_Based_on_Launch_Sheet_Screenshot](This_PC/Desktop/Stuff/school/DATA_CLASS/Challange_1/Outcomes_Based_on_Launch_Sheet_Screenshot.png)
  At a first glance at the chart we can see that the summer months have the highest rate of success for theater type kickstarters. Failuar numbers stay pretty steady much like the canceled number wich also stay pretty consistent with a flat curve.

### Analysis of Outcomes Based on Goals
  For the Outcomes Based on Goals Chart we created a new sheet where we wrote down data solutions taken from the Kickstarter sheet. Using the "=COUNTIFS()" functions we found the number of Successful, Failed and canceled projects at different Project Goal ranges. We then used "=SUM()" to find the total number of projects from all three catagories at different Goal ranges. Finally we found the percentages using a simple division formula followed by using the "%" in the tool bar. Once we had our data it was time to make a chart so we used the pivot table function to make a table that we could thenuse to make a chart. The table used the "Goal" as the Axis, and the Values were the Percentages of the three outcomes we had. 
![Outcomes_Based_on_Goals_Screenshot](This_PC/Desktop/Stuff/school/DATA_CLASS/Challange_1/Outcomes_Based_on_Goals_Screenshot.png)
  At first glance we can see an intresting curve. The data intercepets at the three differnet points; first it intercepts at the 20000 mark where the failed rate starts exceeding the success rate. Then it flips back in favor for success at the 35000 to 40000 mark but shortly changing back at the 45000 mark. 
### Challenges and Difficulties Encountered

## Results

  For the Theater Outcomes vs Launch data there are several conclusions drew. With our observations, first thing we found is that for theater kickstarters it's best to intiate the launch Date in May through July at the latest. Best being in May. The second being that Canceled and failed numbers seem to be unaffacted by the time of year as they remain releativly flat throughout the year.
 Result Chart:![Theater_Outcomes_vs_Launch](This_PC/Desktop/Stuff/school/DATA_CLASS/Challange_1/Resources/Theater_Outcomes_vs_Launch.png)

  For the Outcomes based on Goals we see that there are several sweet spots where kickstarters that fall under the "Plays" Subcategory should try to aim for. For smaller projects, it's best to not exceed the 10000 mark since beyond the point the chances of success becomes 50:50. The only time a high goal should be set is at the 40000 to 45000 where the risks are almost identical to what they are at the <10000 mark. 
  Result Chart:![Outcomes_vs_Goals](This_PC/Desktop/Stuff/school/DATA_CLASS/Challange_1/Resources/Outcomes_vs_Goals.png) 

  What the data could use is a greater focus on the types of plays and venuse these Kickstarters are usings. In the case of the Launch Date outcomes we see that summer is a good time to do theater kickstarters, but is that because most events are hosted outside in the weather and winter weather can be trickey and put people off from coming out at the last second. The type of plays or maybe a specific play that is very popular and can encourage people to come out is also an important note. What I think the next step should be is to gather and filter this data and consider that into the planning stage to increase the chances of reaching a desired outcome. I would make create a bargraph showing the most popular plays in the successful category. Then figure out the sorts of number this particaular play brings in to see if it would be suitable for a large or small project. Then I would make a Launch date table to see when is the best time of the year for this play.


