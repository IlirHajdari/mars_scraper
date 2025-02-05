# Mars Data Web Scraping Project

## NOTE ##
The starter code for this assignment was provided by the course/class, which is why I did not rename the folders and continued on from where the course left off.

## Description
This Mars data scraping project is divided into two parts: **Mars News Scraping** and **Mars Weather Analysis**. The project extracts and analyzes data related to Mars' latest news articles and weather conditions using **Splinter** and **BeautifulSoup**.

## Summary

### Part 1: Scrape Titles and Preview Text from Mars News
Mars News Scraping extracts the latest news articles from the Mars news website. Automated browsing techniques are used to navigate the page, identify relevant elements, and scrape the data.

#### Key Deliverables:
- Utilize **Splinter** and **BeautifulSoup** to browse and extract content.
- Scrape news article **titles** and **preview texts**.
- Store each article as a dictionary with `title` and `preview` keys.
- Save the scraped data as a JSON file (optional).

### Part 2: Scrape and Analyze Mars Weather Data
The Mars Weather Analysis part scrapes historical weather data from the Mars Temperature Data Site. The extracted data is structured into a Pandas DataFrame for further analysis.

#### Key Deliverables:
- Use **BeautifulSoup** to extract weather data from an HTML table.
- Convert scraped data into a Pandas **DataFrame**.
- Ensure proper data types for each column.
- Perform exploratory analysis to answer:
  - How many months exist on Mars?
  - How many Martian days' worth of data exist in the dataset?
  - Which months have the lowest and highest temperatures? (Visualization required)
  - Which months have the lowest and highest atmospheric pressure? (Visualization required)
  - Approximate the number of terrestrial days in a Martian year (Visualization required).
- Export the cleaned dataset to a **CSV file**.

## Requirements

### Tools and Libraries

**APIs:**
- Splinter
- BeautifulSoup

**Python Libraries:**
- Pandas
- Matplotlib
- JSON

## Contact Information

For questions or additional information, reach out to me at:
- **Email:** ilir.hajdari111@gmail.com
