# Mission-to-Mars
A Web Scraping App

## Project Overview
The purpose of this project was to create a web scraping app that gathers information from various sources and collects different types of data. The app updates its contents with the most recent data with just one click of a button. The tools and Mars data used in this project is seen in the resources below.

### Resources
    - Data Source:
        - [Mars News](https://data-class-mars.s3.amazonaws.com/Mars/index.html)
        - [Mars Featured Image](https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html)
        - [Mars Facts](https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html)
        - [Mars Hemispheres](https://marshemispheres.com/)
    - Language: 
        - Python 3.7.10
            - Dependencies: Pandas, Splinter, BeautifulSoup, ChromeDriverManager
            - Web application framework: Flask
        - HTML, CSS
            - CSS Framework: Bootstrap 3
    - Software: Jupyter Notebook, MongoDB, VSCode
    - Code:
        - [scraping.py](https://github.com/samanthajpv/Mission-to-Mars/blob/00dd544b1e305a6ec0f4f6908febc7125e923a16/scraping.py)
        - [app.py](https://github.com/samanthajpv/Mission-to-Mars/blob/00dd544b1e305a6ec0f4f6908febc7125e923a16/app.py)
        - [index.html](https://github.com/samanthajpv/Mission-to-Mars/blob/00dd544b1e305a6ec0f4f6908febc7125e923a16/templates/index.html)

## Method 

- **Web Scraping** - Write Python script to scrape web using BeautifulSoup and automate it using Splinter. HTML components were identified through Chrome Developer Tools. Refer to *scraping.py*.

- **Create Web App** - Store data using MongoDB. Use Flask to create the app routes. This file executes the scraping code and renders the Flask template. Refer to *app.py*. 

- **Create HTML Template** - Bootstrap 3 components was used to customize the appearance of the app. See below snapshot of the web app. Refer to *index.html*. 

<p align="middle">
    <img src="" width="200" height="300"/>
    <h5 align="center">Mission to Mars Web Scraping App</h5>
</p>

<p align="middle">
    <img src="" width="200" height="300"/>
    <h5 align="center">Responsive Table in App</h5>
</p>

## Reference

(1) Trilogy Education Services. (2021, August). *Module 10 Challenge*. https://courses.bootcampspot.com/courses/626/assignments/13315?module_item_id=213020