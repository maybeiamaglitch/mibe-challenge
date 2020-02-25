# Challenge

This challenge is designed to test your analytical skills.  

The challenge consists in delivering a report about the food delivery scene in London. You will be evaluated both: (1) the quality of the final report; (2) the quality of the code that generates such a report. In the report, you are required to complete very specific analysis in addition to a portion where you will showcase your creativity by answering a question you find interesting.  

# Software

You are required to use [R](https://www.r-project.org/about.html) to develop the report. R is the go to software when working on a number of tasks, such as data-manipulation, data-visualization, text-mining, statistical analysis, web-scraping, reporting, etc.

Follow these steps to set up R:

- Install [R](https://www.r-project.org)
- Install the [Rstudio IDE](https://www.rstudio.com). Rstudio has many features (e.g., tools for plotting or debugging) that makes working with R much easier.

You can learn more about R from the following introductory resources:  

- [R for data science](https://r4ds.had.co.nz)
- [Happy Git and GitHub for the useR](https://happygitwithr.com/index.html)
- [What They Forgot to Teach You About R](https://rstats.wtf)

# Data

Your analysis should exclusively use the following datasets:

- Restaurants information [download](data/resturants-mibe.rds)
- Restaurants delivery time [download](data/delivery-mibe.rds)

# Analysis

When developing the report, follow closely the structure presented in this section.

## Restaurants Information

In this section, you will analyze the `Restaurant information` dataset with the objective of answering the following questions:  

- Present a column chart with the top 10 neighborhoods by the number of restaurants.
- Present a column chart with the top 10 neighborhoods by restaurant review score.
- Compute the top 10 biggest chains. Present the results in a tabular format. (Use the column `rest_brand` to determine restaurants of the same brand)
- Compute the average menu price and the number of menu items for each restaurant. (The `rest_menu_item_price` column is a list of characters. You might want to use the `by_row` and `map` functions)
- Present in a bar chart the number of items on the menu for the five most expensive and cheapest restaurants. (The number of items can be determined by counting the elements in the `rest_menu_item_price` column)

## Restaurants Delivery Times

In this section, you will analyze the restaurant's delivery times. To perform the following analysis, you will need to join the `Restaurants information` and `Restaurants delivery time` datasets using their `restaurant_id` and `rest_key` primary keys. Answer the following questions:  

- Count the number of neighborhoods where each restaurant delivers. (Each restaurant can deliver to multiple neighborhoods, independently from here the restaurants is physically located)
- Present in a bar chart the top 15 neighborhoods by the number of restaurants where restaurants make deliveries. (You will need to count the number of restaurants that deliver to each neighborhood)
- Compute the average delivery time for each restaurant. (Compute the average of all neighborhoods the restaurant delivers)
- Present in tabular format the top 20 restaurants by fasted average delivery time. In the same table, present the rating score, and postcode. 

## Open Analysis

In this section, you are invited to showcase your creativity as an analyst by developing an interesting analysis. You should open this section by stating a clear "business question," followed by a series of analysis (e.g., charts, tables) that investigate this question. You are also required to narrate your findings.


# Deliverables

You are required to deliver the analysis using an Rmarkdown. You will have to share both the final analysis in PDF and the code that generates that analysis in `.Rmd` format. Furthermore, you are required to upload to Github the Rproject containing the code, pdf, report, and any other file that you used to develop the report. We expect that the code you share can be run downloaded and run on other computers without any configuration.

- Report in PDF.
- Rmarkdown code (.Rmd file).
- URL to Github page where to find the previous two deliverables.
