# Mission-to-Mars

## Overview of Mission-to-Mars
The purpose of the Mission-to-Mars analysis was to develop an automated program to "scrape" relevant and interesting data from various websites about Mars, save the data into a Mongo database, and create a web app to display the data in a coherent, organized, and visually-pleasing manner. Below are the steps of this web-scraping data analysis process:

  - Data from several websites, i.e., recent news about Mars from NASA, a featured image of Mars from the Jet Propulsion Laboratory, a table of Mars facts, and images of the four hemispheres of Mars, were identified as the key components of interest to scrape. 
  - A web app was built to develop an automated program that would scrape these data each time it is run.
  - The web app was updated to ensure it is mobile-responsive and included a few key features to enhance its appearance and appeal:
    - A color design scheme incorporating Mars' reddish tint was developed and implemented to provide aesthetic interest to the webpage (e.g., borders around images, background banners of color)
    - Font styling using bold, underline, and italics was added to key headers to help demarcate the various sections of the website
    - The four hemispheres of Mars were converted to thumbnail images with shadow backgrounds so that users can click to view the hemispheres' full-size images
    - A music feature was added to the top of the webpage so that users can have a unique multi-sensory experience of viewing beautiful images of Mars, learning important news and facts about Mars, and listening to the incredibly powerful and inspiring first movement of Gustav Holst's "The Planets", entitled "Mars, the Bringer of War", which celebrates Mars in all its glory   


## Resources
- Data Sources: The following webpages: https://redplanetscience.com/; https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html; https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html; https://marshemispheres.com/
- Software: Python 3.7.10, Anaconda 1.7.2, Jupyter Notebook, Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo, MongoDB

