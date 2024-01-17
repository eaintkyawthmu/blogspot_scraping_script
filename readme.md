
<a href="https://opensource.org/licenses/MIT/" target="_blank"><img alt="MIT License" src="https://img.shields.io/badge/License-MIT-blue.svg" style="display: inherit;"/></a>  <a href="https://github.com/eaintkyawthmu" target="_blank"><img alt="AngelicML" src="https://img.shields.io/badge/Author-AngelicML-blue.svg" style="display: inherit;"/></a>



You can reach out to me via :

[![Gmail Badge](https://img.shields.io/badge/-Email--me-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:eaintkyawthmu@gmail.com)](mailto:eaintkyawthmu@gmail.com) [![Medium Badge](https://img.shields.io/badge/-Medium-black?style=flat-square&logo=Medium&logoColor=white&link=https://medium.com/@eaintkyawthmu/)](https://medium.com/@eaintkyawthmu/)      [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/eaintkyawthmu/)](https://www.linkedin.com/in/eaintkyawthmu/)   [![GitHub Badge](https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github&logoColor=white&link=https://github.com/eaintkyawthmu/)](https://github.com/eaintkyawthmu) 

# Blogspot Scraping Script

This project contains a Jupyter Notebook that scrapes data from a Blogspot blog. The data includes the title, image source, and post body of each blog post.


## Libraries Used

1. `pandas`: A powerful data manipulation library.
2. `BeautifulSoup`: A library to extract data from HTML and XML files, or in simpler terms, to scrape data from websites.
3. `selenium`: A tool for automating browsers. It provides a single interface that lets you write test scripts in programming languages like Ruby, Java, NodeJS, PHP, Perl, Python, and C#, among others.

## Setup

Before running the script, make sure you have the following dependencies installed:

- `pandas`
- `beautifulsoup4`
- `selenium`
- `webdriver_manager`

You can install these dependencies using `pip`:

``` 
pip install pandas beautifulsoup4 selenium
```

## Note/Summary

The current code is set to scrape the blog at "https://horkhamit.blogspot.com/" as an example. If you want to scrape a different blog, you will need to modify the URL in the code.

The script visits a specified blog, extracts the title, image sources, and text from each post, and stores this information in a DataFrame then continues to navigate to older posts until there are no more left, appending the data from each post to the DataFrame.

The DataFrame is then saved as both a CSV file and a text file for further analysis.


## How to Run

1. Ensure that you have the necessary Python libraries installed. These include pandas, BeautifulSoup, selenium, and webdriver_manager.
2. Open the `blogspot_scrape.ipynb` file in a Jupyter Notebook environment.
3. Run the cells in the notebook to start the scraping process.

## Output

The output of the scraping process is saved in two files: `food_data1.csv` and `food_data1.txt`. These files contain the title, image source, and post body of each blog post.


## License
MIT © [Eaint Kyawt Hmu](https://www.linkedin.com/in/eaintkyawthmu/)

