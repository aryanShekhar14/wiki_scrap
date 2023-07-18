## Features
● A web scraping project to build an extensive database of films produced by a production house, gathering
crucial information like release date, box office, running duration, etc. from their individual Wikipedia pages.<br/>
● Used libraries like BeautifulSoup and Pandas, to automate the extraction of movie data from several web
pages, leading to considerable time savings and enhanced data accuracy.<br/>
● Incorporated the OMDB API, allowing for the extraction of crucial metrics like IMDB and Rotten Tomatoes
ratings for each film, boosting the database with measuring scores for improved analysis and comparison.</br>
## The following dependencies are required to run WikiScrap:
Python 3.x<br/>
BeautifulSoup<br/>
Pandas<br/>
## Installation
1. Clone the WikiScrap repository:<br/>
`git clone https://github.com/aryanShekhar14/wiki_scrap`<br/>
2. Change to the project directory:<br/>
`cd wiki_scrap`<br/>
3. Install the required dependencies using pip.
## Usage
1. Run the wiki_scrap.ipynb file in jupyter notebook.
2. The code will automatically scrape movie data from the specified Wikipedia pages and store it in a CSV file.
3. Once the web scraping is complete, the OMDB API will be utilized to retrieve additional metrics for each film.
4. The final dataset, including both scraped and API-fetched data, will be stored in a CSV file for further analysis and comparison.
