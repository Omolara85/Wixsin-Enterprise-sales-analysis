# Wixsin-Enterprise-sales-analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Result](#result)
- [Recommendation](#recommendation)
- [Limitation](#limitation)
- [Reference](#reference)

### Project Overview

This dataset project was provided by Quantum Analysis NG, it all about an enterpise sales information, using the Index Match to bring out consolidation table in order toidentify the daily growth in sales, segment growth E.T.C 

### Data Source

Sales Data; the primary dataset use for this analysis is "INDEX MATCH"EXCEL FILE, containing information about each sales and product made by the company.

### Tools

- Microsoft Excel - Data cleaning
   -  [Download her](https://microsoft.com)
  
### Data Cleaning

In this data cleaning phase i have to study the dataset critically, explores and cleaned using  Index function to combine all the table in this dataset anduse other function like IFS and TEXT function. 
NOTE; before working or editing the table i have to structure each table in order to call out the table when combining to consolidation table.
I create my pivot table to design my dashboard for in-depth analysis.

### Exploratory Data Analysis

This are the Executable Decision
- Is revenue growing on Monthly base?
- What days of the week do the company make the most revenue?
- What is the proportion of category to total revenue?
- What is the contribution of each state to the total revenue of the company?
- What segment has the highest amount of revenue?
- What are the top 5 best-selling product?

### Data Analysis

Include some interesting code/function used in dataset

'''EXCEL
- =IFS([@ManufacturerID]=1,"Abbas",[@ManufacturerID]=2,"Aliqui",[@ManufacturerID]=3,"Barba",[@ManufacturerID]=4,"Currus",[@ManufacturerID]=5,"Fama",[@ManufacturerID]=6,"Leo",[@ManufacturerID]=7,"Vanarsdel",[@ManufacturerID]=8,"Natura",[@ManufacturerID]=9,"Palma",[@ManufacturerID]=10,"Pirum",[@ManufacturerID]=11,"Pomum",[@Manu
- facturerID]=12,"Quibus",[@ManufacturerID]=13,"Salvus",[@ManufacturerID]=14,"Victoria")
- =TEXT([@Date],"DDDD")
- =INDEX(Location_Table[State],MATCH([@Zip],Location_Table[Zip],0))

### Result
summary of this dataset is
- Alberta and Ontario has the higest contribution revenue to the company
- the product category is the best performing category in terms of sales and revenue

### Recommendation
The company should re-strategies and bring in C.S.R  to Quebec state inother to create sympathy in to the mindset of the people to help increase in revenue

### Limitation 
i have to study the dataset explored and cleaned.

### Reference
Zoom video by OLUWO Zainab Omolara

- [Download on Linkedin](https://www.linkedin.com/posts/zainab-oluwo-774a89304_im-here-again-to-share-my-analysis-on-wixsin-activity-7209912067493900288-FWof?utm_source=share&utm_medium=member_desktop)



  
  
