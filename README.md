# Web-scraping-challenge

## Step 1 - Scraping
Complete your initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter by visiting NASA Mars News, JPL Mars Space Images - Featured Image, Mars Facts, and USGS Astrogeology site to obtain data on Mars.


## Step 2 - MongoDB and Flask Application
Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.

Start by converting your Jupyter notebook into a Python script called scrape_mars.py with a function called scrape that will execute all of your scraping code from above and return one Python dictionary containing all of the scraped data.

Next, create a route called /scrape that will import your scrape_mars.py script and call your scrape function.

Store the return value in Mongo as a Python dictionary.

Create a root route / that will query your Mongo database and pass the mars data into an HTML template to display the data.

Create a template HTML file called index.html that will take the mars data dictionary and display all of the data in the appropriate HTML elements. 


![Mars Homepage](https://github.com/AliceSartori/Web-scraping-challenge/blob/main/Screen%20Shot%202021-02-26%20at%207.17.17%20PM.png)

![Mars Hemispheres](https://github.com/AliceSartori/Web-scraping-challenge/blob/main/Screen%20Shot%202021-02-26%20at%207.17.06%20PM.png)
