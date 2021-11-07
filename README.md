# Technical-Assessment
Author: Faith Tan
Date created: 4 November 2021

This code was created with the task at hand in mind, and in order to showcase best what I know how to do, I decided to produce 3 visualizations with Shiny in Markdown.
The code has been labelled with what I deem as appropriate notation to help the reader understand my general thought process. I also carried out a general clean up of the 
data.

The 3 interactive visualizations are as follows:
1. Mortality throughout the Years
The main thought process for this idea was "which entity had the highest death rate in each year?".
For this task, I combined two datasets (malaria_inc & malaria_deaths) in order to obtain a death rate per 100,000 people. Following this, a slider was created for
the available years in order to showcase the plot for each one. As describe in Markdown, I found that it was unpleasant visually to allow overlapping words on the x-axis,
so I chose to use the codes for each entity, and removed all entities that did not have a code or data for all 4 years. The entity "World" was removed as well as it did
not fit into the idea of this visualization.
  
2. Deaths by Age Group and Entity
For this visualization, the main idea was "what does the trend of deaths for each age group and entity look like over the years?".
This visualization did not need as much "cleaning up" as the first one, but allows for the selection of 2 inputs to isolate more specific information for the viewer.

3. Summary of Age Groups in a particular Entity and Year
This visualization's idea was "show an overall summary of deaths in each age group for any entity and year".
I selected a data table as we had already previously seen two types of graphs, and a numerical visualization is always informative. 
