# Recipes-Data
Data analysis project on top recipes, web scraped from allrecipes.com

# Project Summary
* Web scraped ~4,000 recipes from Allrecipes.com using Python's BeautifulSoup and JSON libraries.
* Using Pandas, cleaned the data. This included extracting ingredient names, converting various cook time formats to numerical values, and locating HTML elements across multiple webpage layouts.
* Generated charts of the most common ingredients, title keywords, and instruction verbs using Matplotlib.
* Analyzed distribution of recommended serving sizes and cook times, and generated visualizations.

# Instructions to Run or View Project
* To view analysis, run the 'Recipe Data Analysis' notebook.  To skip straight to the figures, open the 'figures' folder and view the image files.

* Recipe data is saved in the file 'recipes.json'.  To scrape additional data, run the 'Web Scraper' notebook, setting the first_page and last_page parameters to specify the range of pages to scrape.
