# Data Visualization Skills Assessment

This repo contains the Jupyter Notebook, results, and presentation on a data visualization skills assessment based on a simulated dataset of Walmart Black Friday sales data.

***

## `Correction!`

While refining my code, I realized I had made a mistake with my graph that displayed male and female sales on the same graph:

![Incorrect Graph](/results/occup_all_sales_gender.png)

I mistakenly just stacked both charts for male and female sales per occupation on top of one another without considering the x-axis--the data is in the correct order relative to themselves but they don't match up with the occupation categories.

**Here's a corrected graph:**

![Correct Graph](/results/occup_all_sales_gender_CORRECTED.png)

***

## Assignment

**Question:**

>  The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and **the various other factors** to help the business make better decisions. For example, they want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men?

**Tasks:**
   
> Analyze the provided data and provide insights to the best of your      abilities. Include the relevant tables/graphs/visualization to explain what you have learned about the market. Make sure that the solution reflects your entire thought process including code and preparation of data.

>  Use Python and Pandas to provide basic statistics on the data, produce data visualization with numerical data, show visuals of purchases by other variables. Display relevant statistics and summarize actionable insights that would contribute how to Wal-Mart should market to this audience.

**Deliverables**
 
 > Email results in a report or presentation form

### Data Description

> The company collected the transactional data of customers who purchased products from Walmart Stores during Black Friday. The dataset in `walmart_data.csv` has the following features:

`User_ID`

`Product_ID`

`Gender` - sex of a customer

`Age` - age in bins

`Occupation` (masked)

`City_Category` - category of the city [A, B, C]

`Stay_In_Current_City_Years`: number of years a customer stays in their current city

`Marital_Status`

`Product_Category `(masked)

`Purchase` - purchase amount



**Practicalities**

 > For simplicity, you may assume that 50% of Walmart's customer base are Male and the other 50% are Female.

***


## Technologies Used

* Python
* Pandas
* Numpy
* Matplotlib 
* Jupyter Notebook
* Visual Studio Code
  


## Project Structure

**/datasets**  
- `edited_wm_data.csv`
    - Sandbox of original file where I validated data through Excel
- **`walmart_data.csv`**
    - Original provided dataset, unaltered


**/report**  
- `BlackFridaySalesReport.pdf`


**`walmart_datagh.ipynb`** 
    - Code and notes

## Links That Were of Help
- For help importing images
    - https://stackoverflow.com/questions/58862684/can-not-render-images-in-ipynb-files-on-vscode
- Help with plt.pie()
    - https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html#matplotlib.pyplot.bar


## TODO:

1. Refine `Products` section
2. Continue with updates here if needed
