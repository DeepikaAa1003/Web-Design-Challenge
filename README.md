## Web Visualization Dashboard (Latitude)

## Background

Languagesd used: Python, HTML, CSS, Bootstrap


The website link as follows: https://deepikaaa1003.github.io/Web-Design-Challenge/


## Latitude - Latitude Analysis Dashboard with Attitude

Created a visualization dashboard website using visualizations we've created in a past project. Plotting weather data analysis 

In building this dashboard, created individual pages for each plot and a means by which we can navigate between them. These pages contains the visualizations and their corresponding explanations. It has a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.


The website consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. A sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. 
    * The data comes from the `.csv` file as HTML
The website at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). 

![alt text][logo]

[logo]: https://github.com/DeepikaAa1003/Web-Design-Challenge/blob/master/Resources/assets/images/Demo.gif "Basic walkthrough"



