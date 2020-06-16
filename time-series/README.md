
# Mod 4 Project - Time Series Modeling

For this MOD 4 project I went ahead and chose the Time Series modeling, which gives us the task of finding the 5 best zipcodes to invest in for our stakeholders. I will be acting as a consultant to stakeholders that are interested in seeking some investment opportunities on the west coast. We will look at Los Angeles and two of its most popular areas; Downtown L.A.(DTLA) and Santa Monica(SAMO). 

Using the Return on Investment(ROI) statistic we will make a solid recommendation on whether or not L.A. is a place to find a sound investment. It will also give us some insight as to what could happen in the event of another financial crisis like we saw in 2008. 




## Contents

- README.md - currently there!

- CONTRIBUTING.md - a reference to the people who made this project possible.

- LICENSE.md - the required license information.

- student_notebook.ipynb - the Jupyter Notebook containing the finalized code for this project.

- zillow_data.csv - the file containing the dataset which comes from Zillow (https://www.zillow.com/research/data/)

- zip_code_database.csv - file containing zip code latitude and longitude (https://www.unitedstateszipcodes.org/zip-code-database/)

- MOD 4 V2 PROJECT.pdf - pdf of my project presentation


## Libraries and Packages

- numpy
- pandas
- matplotlib.pyplot
- statsmodels.graphics.tsaplots import plot_acf, plot_pacf
- statsmodels.api
- folium

## Results

We have seen a very interesting result from our modeling. In the past our data showed that DTLA was a better place for investment than Santa Monica even for a short term return at two years. According to our results Santa Monica would seem like the better option for a 5 year return; predicting a 20% gain with a potential gain of 146%, but a potential loss of 105%.

Top Five Zip Codes to Invest (Downtown L.A. & Santa Monica)
- 90404(SAMO): 98% average six month return
- 90405(SAMO): 97% average six month return
- 90013(DTLA): 95% average six month return
- 90012(DTLA): 73% average six month return
- 90014(DTLA): 67% average six month return

Very interesting result considering all the past data pointed at Downtown L.A. as an area for a sound investment, regardless of the losses seen in the economic crisis of 2008. Santa Monica has come out on top of the list with two different zip codes showing the largest increase in relation to our chosen areas of DTLA and Santa Monica. Investing close to the water seems to be a good idea.

## Future Work

Collect more recent data of home values to help us better understand what is currently going on with the real estate market in Los Angeles. Using this data we can more precisely pin point the correct zip codes to recommend rather than using the historic data we have.

Investigate the data further to better understand the trends and reinforce the predictive capability of the model.

Since we only looked at two areas of the city, further research into the other inland areas and beach areas to see the comparison and find other opportunities that weren't immediately seen.

Use population, and proximity to freeways and public transportation to see if there is any significant affect on the zip codes average home value.

## Authors

Jose J. Villalobos