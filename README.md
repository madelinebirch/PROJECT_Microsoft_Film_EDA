# Microsoft's Journey into Film
## 3 Key Business Recommendations for Optimal ROI

![Microsoft](Images/microsoft2.png)

Author: Madeline Birch

# Overview

This purpose of the project is to advise stakeholder Microsoft, a large technology corporation devoted to "empower[ing] every person and every organization on the planet to achieve more”, on how to suceed in the film industry by creating their own film studio and releasing productions to audiences worldwide. The goal is to have Microsoft join the pantheon of successful film studios, like Warner Bros., Paramount Pictures, and 20th Century Studios.







![pantheon_readme.png](attachment:pantheon_readme.png)


# Business Problem

##### Determining dependent variable
  When pondering the possible dependent variables I could measure the data against, I decided that 'profit' would be the most suitable. For a corporation like Microsoft, it made most sense to me that total net profit would be of highest interest to stakeholders. Where gross revenue can give an impressive look at how a specific film did in the boxoffice, both domestic and worldwide, net profit gives us the most accurate view on the company's financial health following an investment as grand as a movie production. Net profit provides payment to C-suite, reimburses production expenses, and increases the overall value of the company for shareholders across the globe.

# Data

Using movie themed datasets provided by Flatiron as well as a movie datset scraped from Kaggle (https://www.kaggle.com/datasets/fajim123/movies-metadata), we identified 3 variables that stood out as most helpful when giving recommendations on how to maximize profit: budget, genre, and release month.

# Methods

This project broadly scrutinizes data read through DataFrames using the PANDAS library. Through methodical data cleaning, manipulating, sorting and low level mathematical analysis (mean, median, mode, categorization), we were able to come up with findings that reflected general trends in genre popularity, budget, and the time of year in which high profiting films are released.

# Outcomes

### Independent variable 1: budget 

After sorting the data into low (up to 10 million USD), mid (between 10 and 100 million USD), and high (between 100 and 500 million USD), we found that high budgets tend overall to yield high profits. A high budget of over 100,000,000 USD can yield profits up to 1,433,854,864 - 2,351,345,279 USD. That's billions of potential dollars for Microsoft. They must ensure they spend high budgets wisely by hiring the best writers, actors, and production teams available to build the highest profitable film studio possible. A boxplot shows a high budget to high profit correlation. The box indicating high budget prodution is much longer and higher than the low and mid budget boxes, which shows that 50% of high budget films have a budget of over 100,000,000 and generate the highest profit. Microsoft has the potential to be as successful as James Cameron's Avatar, which made over 2 BILLION USD in profit! Wow.



![boxplot_readme.png](attachment:boxplot_readme.png)

### Independent variable 2: genre

After manipulating and analyzing the data to find which genres have trended to yield highest profits, we come upon the top 4: Action, Family, Adventure, and Science Fiction, all of which combined yield an average profit between 782,465,326 USD and 940,063,384 USD, with Action averaging the highest. WOW! Make an action movie, Microsoft! Think Top Gun, Avengers, anything with high intensity action sequences and fight scenes with a hero vs. villain plot arc. 



![barchart_readme.png](attachment:barchart_readme.png)

### Independent variable 3: release month

The time of year in which a film is release matters greatly to the studio's profit outcomes. Let's make a copy and sort through our previous DataFrame, clean it, and sort it to see which months yielded highest net revenues. A line graph profits skyrocketing between May and July, peaking the highest in June, with average profits hitting 16,142,140 USD. Profits spike again during the Holidays, hitting 11,571,850 USD in December. If Microsoft wants to be successful and reap the highest possible profit, they ought to market and release their films as either Summer or Christmas/New Years blockbuster events.





![linegraph_readme.png](attachment:linegraph_readme.png)

# Conclusion & Next Steps

If Microsoft desires succcess in the film industry by earning highest possible profits, consistency is key on 3 variables: high production budget, action/adventure-oriented genre, and releases close to or within the month of June. Next steps to consider include a November or December release date to eliminate summer blockbuster competition and a scfi/fantasy film production to rival action/adventure releases.

### For further discussion, please contact me:

E-mail: mbirchhn@gmail.com
GitHub: https://github.com/madelinebirch
LinkedIn: https://www.linkedin.com/in/madeline-birch-164000b5/

# Repository structure

├── Data

├── Images

├── notebook.ipynb

└── README.md

├── microsoft_presentation.pdf
