# BST_for_Webscraping_Data
Web-scrapes data from Wikipedia, and builds a binary search tree with the data to allow easy sorting and search.

1. What is your project idea about?
The plan for our project is to web-scrape data from Wikipedia, and build a binary search tree with the data to allow easy sorting and search. Finally, we will list a few statistical analyses made from our sorted data.

2. If you use any datasets, describe the dataset and provide how one can access and download it.
We plan on sourcing our data from the Wikipedia page for recorded Category 5 Atlantic Hurricanes. Anyone can access it and we will retrieve the data using APIs.

3. Describe your design for main packages, classes, methods, functions, and iterations between them.
Our program will be made in Jupyter Notebook, with each "section" of the project separated by cells. For example, one cell will include the web-scraping, another will include the creation of the binary tree and its constituent functions, and one for the calling all the functions. We plan on creating one function to handle the web-scraping, and a special class to be built upon the existing BST implementation in class to sort our data.

4. Describe any libraries that you use.
We will be using the BeautifulSoup API and the Requests API to ensure Wikipedia allows us to scrape the data and then subsequently scrape it. We will also use Pandas to store the data in data frames, and Seaborn to plot our data.

5. Design some Test cases that can test the correctness of your software.
Since our program is fairly straightforward, there isn't much in the way of user input. However, we plan on outputting multiple sorted lists of our data to ensure the program works properly, as well as a sorting function that can take in user input and sorts the data by the given input. We plan on calling this function on multiple valid and invalid columns to make sure the sorting us happening properly.

6. What is your current expectations of your software? For example, do you expect that it works well? What are the expected weaknesses?
We assume we will run into some hiccups with properly web-scraping the data, as well as cleaning the data before loading it into the binary tree. We need to convert our data from a dictionary into another data type, as dictionaries by design cannot be sorted. Once the data is properly loaded and the tree is built, we expect the rest of the program to be relatively simple.
