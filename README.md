# Hedging Bits
Project 1 - Chelsea Senter, Darren Raymond, Emi Lopez, Meredith Johnson, and Ryan Lassiter<p><p>

Welcome to our first project!<p><p>


## Overview
In this project, we wanted to analyze Bitcoin's reaction to several events that occurred in 2020. Obviously, Covid-19 has been the #1 story of 2020, so we wanted to look at that as well as the summer protests due to social unrest following the death of George Floyd and the 2020 U.S. Election. <p><p>

**Hypothesis**<p>
If bitcoin functions like a gold investment, then uncertainty experienced with Covid-19, Social Unrest (anchored by George Floyd) and the US Election will cause investors to leave the market (Dow) and invest in bitcoin and gold.<p><p>

**Questions**<p>
* Did bitcoin yield a higher return than the Dow over 2020?<p>
* Is bitcoin favored during US economic downturn (GDP benchmarkers)?<p>
* How did bitcoin perform over Gold during the Pandemic as a safeguard alternative investment? <p>
* Did investors hedge with bitcoin during the Covid-19 pandemic?<p><p>

**Summary**<p>
With Covid-19 and the George Floyd protests, bitcoin and gold paralleled each other in trend, but as the election neared, bitcoin sharply rose while gold declined<p><p>

## Data Sources
We used 3 main data sources: Bitcoin (Coindesk API), Dow Jones Industrial Average (FRED DJIA CSV), and Gold Prices (Nasdaq Historical Data CSV).<p>
![Bitcoin](visuals/coindesk-logo.png)
![DowJones](visuals/fred-logo.png)
![Gold](visuals/nasdaq-logo.png)
## Data Cleaning
We had 3 main themes in data cleaning:<p>
1. Column Manipulation: One of the first cleaning tasks we dealt with was to rename the column headers in all data sources to match each other. This was necessary for a successful merge later on based on the date. 
2. Datetime conversion: In order to merge all datasets by the date, we had to further clean the data by converting all date columns to the same datetime format.<p>
3. Missing data: Bitcoin is a 24/7 trading platform, whereas the DJIA and Gold are closed during weekends and holidays. Therefore, when we combined all 3 data sources, there were noticable gaps in the DJIA and Gold line charts compared to Bitcoin. To fix this, we decided to drop the weekend and hoilday values so our data could be compared equally.<p> 

## Data Visualization

## Repository Organization
### Main Project File
In this repo you will find our main project file, named: **project-nb.ipynb** <p><p>
 
### Data Folder
The data linked to our project file is located in the **data** folder.<p>
  For this data, we used the Dow Jones Industrial Average data and Gold prices data.<p>
  Additionally, our presentation file is also located in this folder.<p>

### Draft Folder
Our draft notebooks are located in the **Drafts** folder. We created branches for each person in the group instead of what task was being worked on. Therefore we are not including these notebooks as part of our final project, but we felt it would help visualize the progression of our ideas. <p><p>

