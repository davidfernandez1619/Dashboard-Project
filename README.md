# Psychological disorders visualization project

![image](https://github.com/davidfernandez1619/Dashboard-Project/assets/38441372/b26d7011-46b2-40fc-897b-618700fc8491)

## Introduction

As a Psychology graduate, and since mental health is (fortunately!) becoming more visible and talked about worldwide, I decided to do a visualization project about three of the most common psychological disorders: depression, alcohol consumption and drugs consumption. 

The three of them are pretty known by most people, but here you have a little bit more info about each of them in case you're interested ([Depression](https://www.psychiatry.org/patients-families/depression/what-is-depression), [Alcohol disorder](https://www.mayoclinic.org/diseases-conditions/alcohol-use-disorder/symptoms-causes/syc-20369243), [Drugs disorder](https://www.mayoclinic.org/diseases-conditions/drug-addiction/symptoms-causes/syc-20365112)). 

To do this project, I followed these steps:

## Step 1: Extract and clean CSVs:

I found on [Kaggle](https://www.kaggle.com/) a CSV containing the prevalence (percentage of the total population that meets the requirements for suffering from a disorder) of several psychological disorders, from 2004 to 2017. I cleaned the data and saved the file (see the whole process [here](https://github.com/davidfernandez1619/Dashboard-Project/blob/main/Notebooks/1-%20Cleaning.ipynb))

Also, I took from [INE webpage](https://ine.es/) (Spanish Statistics National Institute) socioeconomic factors data from Spain, like purchasing power, CPI (Consumer Prices Index), gross salaries and unemployment. I also cleaned them a bit and took the years that interested me (see the whole process [here](https://github.com/davidfernandez1619/Dashboard-Project/blob/main/Notebooks/3-%20Socioeconomic%20data.ipynb)). 

## Step 2: Create visualizations:

For this project I used the software [Tableau](https://www.tableau.com/es-es), which allows you to create interactive graphics. 

You can see my project in my [**Tableau Public profile**](https://public.tableau.com/app/profile/david.fern.ndez6995/viz/ProyectoVisualizacin_16929574674720/Historia1). 

You will see a History containing three different dashboards:

**-Dashboard 1:** *'World'*. This dashboard shows a general view of the prevalence of the three disorders worldwide. We can see three maps (one for each disorder), where the countries are colored gradually depending on their prevalence. On the right of each map, you can see a graph that contains all the countries arranged according to their prevalence in descending order. 

All the maps and graphics change depending on which year you choose on the filter (from 2004 to 2017). You can also press 'play' and see in a visual way how the colours of the countries change each year. 

The goal of this dashboard is to have a bird's-eye view of the general prevalence of each disorder per country, and see how it evolves overtime. You can explore your country and continent if you want and see for yourself. 

**-Dashboard 2:** *'Spain'*. This dashboard focuses specifically on Spain. I took four socioeconomic factors to see how they correlate with each disorder: 

* **Purchasing power:** economic capacity of a person or a community to acquire goods and services. It's measured as euros (available rent a person has to buy goods and services). 

* **CPI (Customer Price Index):** numerical value that reflects the variations in prices in a given period. It's measured as a percentage.
  
* **Gross salary:** total income (before taxes) a worker receives from his/her work during a given period. It's measured in euros. 

* **Unemployment:** situation of the person who is able to work but does not have a job or has lost it. It's measured in percentage (based on the total population able to work). 

The dashboard shows how each disorder correlates with each factor. As you can see, most of the disorders have a very-strong or strong correlation with each factor (except a few exceptions, like alcohol disorder-gross salaries and purchasing drugs disorder-purchasing power). 

This data suggests that these factors have an influence on population's mental health and viceversa. 

## Next steps: 

* Add socioeconomic factors data about more European or world countries, to see if they also correlate with these mental health disorders. 

* Add more psychological disorders. It would be interesting to study how other disorders behave worlwide, like anxiety, schizophrenia or bipolar disorder.

* Add population data. This will help to better understand and contextualize prevalence. It's not the same to have for example a 3% prevalence of depression in a country with a population of 1M people, than in a country with 300M people.

## Tools: 

* [**Python**](https://www.python.org/)
* [**Pandas**](https://pandas.pydata.org/)
* [**Tableau**](https://www.tableau.com/es-es)


Feel free to download the project and interact with it, to see which conclusions you can get by yourself. Thank you!!



