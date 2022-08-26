# Responsive Weather Dashboard Web-Design Deployed to GitHub Pages: https://khadra1.github.io/web-design-challenge/
HTML-CSS-Data-Visualization



# Web Design
I designed a 7 page responsive website dashboard for 500+ cities around the world from visualizing weather data.`Python` was used to export cities data from OpenWeatherMap.org `csv` file into `HTML` table, and `Bootstrap`, `HTML`, `CSS` for the website layout and responsiveness.

* An explanation of the project

* Landing Page:

* Four visualisation pages - latitude vs: max temperature, humidity, cloudiness, or wind speed. With links to each visualizations page. Clicking an image takes the user to that visualization. And visualization navigation on every visualization page with an active state for the one you're currently on.

* Comparisons page which contains all of the visualizations on the same page so they can easily be compared with each other:

* Data page that displays a responsive table containing the data used in the visualizations. Table created from `cvs` file exported into HTML using Python and Pandas.

  

At the top of every page, the website must have a navigation menu with the following elements:

* It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website was deployed to GitHub Pages, with the website working on a live, publicly accessible URL .
e.


* I used CSS media query that Bootstrap and `@media` for the navigation bar as well as to ensure website works at all window widths or sizes.
