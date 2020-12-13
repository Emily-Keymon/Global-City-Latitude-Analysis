### Click here for website:  https://emily-keymon.github.io/Global-City-Latitude-Analysis/

# Global City Latitude Analysis
The goal of this project was to develop a website using HTML, CSS and Bootstrap to present the results from the Global Weather Data Analysis project.  

----

## Does the weather change the closer you get to the equator? Let's use data to find out! 
* A Python script was written to visualize the weather of over 500 cities across the world with varying distances from the equator. 
* This dataset was assembled using an OpenWeatherMap API call. 
* Once the data was gathered, Matplotlib, a Python library, was used to plot max temperature, humidity, cloudiness and wind speed vs the city's latitude. 

## The website consist of 7 pages total, including:

* A landing-page containing:
  * An explanation of the project.
  * Links to each visualizations page. A sidebar containing preview images of each plot. Clicking an image takes the user to that visualization.
* Four visualization-pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparisons-page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A data-page that:
  * Displays a responsive table containing the data used in the visualizations.
  * The data came from a `.csv` file and was converted to HTML using Pandas in Python.
* The website has a navigation menu at the top of every page that:
  * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  * Is responsive (using media queries). 
  * The website is available by GitHub pages.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. 
