# CRISP-DM-Analysis-on-Berlin-Airbnb

CRISP-DM-Analysis-on-Berlin-Airbnb is a project based on R, using the CRISP-DM method to produce an useful market report for prospective visitors and hosts of the service. 

The project started in July 2021 by [mikerabs](https://github.com/mikerabs) and Klaire Pham as the final assignment of LACOL Introduction to Data Science course. 

⭐️ Please star our project if you found it interesting to keep us motivated 😃!

---

For more information, feel free to read the our [report](docs/report.pdf).

## Idea
The idea is as follows:

- **Goal**: Given the data by Kaggle, we want to find the answers to market questions, specifically the factors that affect the price of the listing and the experience of the visitor. Following two tracks: maximizing experience and minimizing cost, we want to find out the best neighborhood and number of guests included to achieve either scenario. The specific questions are: 
1. What are the most high-rated room type? Most highly regarded neighborhood?
2. Does popularity always equate high ratings, thus better experience?
(Note: In other words, knowing that number of reviews per month indicate the listing’s popularity (reviews are mandatory to AirBnB users), what is the correlation between number of reviews per month and rating scores.)
- **Preparing the dataset**: We access the data from Kaggle, then do explanatory graphing with it to figure out potential relationships. After developing our research questions and finalizing our lists of useful variables, we clean the skewed data and make training and test sets. 
- **Training and testing the model**: We use different linear regression models and evaluate their reliability based on the p-values, residual charts, and industrial knowledge. We assess the impacts that the data cleanning process and the data quality may have on the models. 


## Folders/Files:

- **r-code**: This is the R mark-down file which implements the graphing and produces the report. 
- **report.pdf**: Report of this project. Read it to see our results and conclusions.

## Training:
To prepare the training and test sets follow this procedure:

1. Download the dataset in pdf from [Kaggle](https://www.kaggle.com/brittabettendorf/berlin-airbnb-data) and save them in the same folder as the r-code file. Only listings.csv and listings_summary.csv are needed for this implementation. 
2. Run and knit the r-code file on RStudio.
	- **Note**: This will produce the same report as the file we include here. 
	
## Critical issues	
- Do not change the names of the data files, this could provoke problems in the code.

## Licensing
- There is no licence. Don't hesitate to use my library. It is straight forward to use and if you use it, please give me feedback.
