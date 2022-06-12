# Web-Design-Challenge

# Web Design Bootcamp Assignment - Web Visualisation Dashboard 

https://user-images.githubusercontent.com/96545188/173207639-d7a056ad-2eb4-410d-8f05-2bb7b0773d98.mp4

## Background

<i>Data is more powerful when we share it with others!</i> 
Use HTML and CSS to create a dashboard featuring previous analysis from a past assignment.

## Instructions 

For this assignment, I had a choice to create a website by using visualisations that were created in Python-APIs assignment, or use the [weather data](Resources/cities.csv) provided.

- Build a dashboard
- Create individual pages for each plot 
- A way to navigate between them

These pages must contain visualisations and descriptions. Also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements

For reference, review the video above. 

The website must consist of seven pages in total, including:

* A landing page containing the following elements:

  * An explanation of the project

  * Links to each visualisations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualisation.

* Four visualisation pages, stored in the `images` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualisation for the selected comparisons (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the `assets/images` folder.

  * A paragraph describing the plot and its significance.

* A Comparisons that does the following:

  * Contains all of the visualisations on the same page so they can easily be compared with each other.

  * Uses a Bootstrap grid for the visualisations.

    * The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.

* A Data page that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component.  

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML.

At the top of every page, the website must have a navigation menu with the following elements:

* It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualisation page.

* It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It should be responsive (using media queries). The navigation bar must be similar to the example provided.
