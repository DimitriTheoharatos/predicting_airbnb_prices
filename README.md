# predicting_airbnb_prices

In this project, I scrape hundreds of Airbnb listings, extracting several features of interest in order to predict the optimal
price to set an Airbnb listing using linear regression and regularization. 

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)


### Files

`Scraping and Feature Engineering.ipynb` --> This notebook covers the web scraping methodology and data cleaning process.  

`EDA.ipynb` --> Covers exploratory analysis of our features of interest.  Visualizations are used to convey significant relationships. 

`Modeling.ipynb` --> Contains the bulk of the modeling and algorithmic analysis. 

`cleaned_data.csv` --> The cleaned file that is written to after the scraping notebook.

`modeling_data.csv` --> Used in conjunction with the modeling notebook. 


### Run

In a terminal or command window, navigate to the top-level project directory and run the following command:


```bash
jupyter notebook
```

This will open the Jupyter Notebook software and project file in your browser.

#### Data:

 * airbnb (http://airbnb.com)
 * rentcafe (http://rentcafe.com)
  
**Important Features**
- `reviews`: the number of reviews the host as received. 
- `ratings`: the rating of the host on a five-point scale. 
- `private_room`: if the listing offers a private room.
- `entire_place`: if the listing offers the entire listing.  
- `plus`: whether or not the host is considered a "plus" host.  
- `rental_price_norm`: an engineered feature that includes the median rental price for each district. 
- `shared_room`: if the listing offers a shared room.
- `number_of_beds`: the number of beds the listing offers. 
- `number_of_guests`: the number of guests the host can offer. 

There are several more features that as pertinent not listed here. 

**Target Variable**
- `price` the price that the host the Airbnb should set their listing to.
