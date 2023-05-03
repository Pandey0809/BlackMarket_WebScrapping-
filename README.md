# BlackMarket_WebScrapping

BlackMArket_Webscrapping as the name suggest is an web scrapping project based on python programming language.

To run the project use
1. git clone [GitHub Repo](https://github.com/Pandey0809/BlackMarket_WebScrapping-.git)
3. Create a python virtual environment for running the Jupyter Notebook
2. Open the file **webscrap.ipynb** in Jupyter notebook 
3. Update your User Agent 
4. Run all the entire code
5. The results should appear in a .csv file by the name "blackmarket_data.csv"

# Project Details

## Dependencies

1. This is a list of the necessary libraries needed to run a code. The libraries are:
* bs4
* pandas
* requests
* numpy
* matplotlib
* seaborn

2. The Project is run in [Jupyter Notebook](https://jupyter.org) environment

## Working

* The project uses python requests library to get the data from [BlackMarket](https://www.backmarket.nl/nl-nl/?gclid=CjwKCAjwjMiiBhA4EiwAZe6jQzHwBs5FU_jtB6RcnCoql3eN_fXFxV8YqNGD11aM5SzI-LAwpbG2_xoC32cQAvD_BwE)
* The initial web address is set for iphone search query but it can be modified to search other products
* Python Beautiful soup and string functions are used to extract and clear HTML data 
* Finally the data is saved in an .csv format
* Now this data can be used for data analysis (example to check corelation between price drop and user ratings)

<img width="783" alt="Screenshot 2023-05-03 at 09 43 55" src="https://user-images.githubusercontent.com/56840145/235858355-2a1109a1-ff1b-436b-a7fd-f1462700e0f1.png">



