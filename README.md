# Homework 5: Readme

## Creating and connecting GitHub repositories: Homicides in Baltimore, MD

This homework aimed to show how to create GitHub repositories and connect our R projects to the online repositories with structured and organized project we ensure better management of large data sets and our code. This particular homework had us working with [The Washington Post](https://github.com/washingtonpost/data-homicides/tree/master) data of 52,000 criminal homicides over the past decade in 50 of the largest American cities. Homework 5 wanted us to look at just Baltimore, MD homicides.

Options for HW 5: 

1: Pick one city in the data. Create a map showing the locations of the homicides in that city, using the sf framework discussed in class. Use tigris to download boundaries for some sub-city geography (e.g., tracts, block groups, county subdivisions) to show as a layer underneath the points showing homicides. Use different facets for solved versus unsolved homicides and different colors to show the three race groups with the highest number of homicides for that city (you may find the fct_lump function from forcats useful for this).

2: Recreate the graph shown below. It shows monthly homicides in Baltimore, with a reference added for the date of the arrest of Freddie Gray and color used to show colder months (November through April) versus warmer months (May through October). There is a smooth line added to help show seasonal and long-term trends in this data.

[plot](https://geanders.github.io/RProgrammingForResearch/figures/hw_5_plot.png)

The work found in this specific repository worked to accomplish option 2. You will see a history of different commits that works through filtering out the information for just Baltimore and creating the plot. 