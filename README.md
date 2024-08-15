<h1> Historical Olympic Medal Analysis </h1>

<img src="images/readmeLogo.png" width="800" height="500">

## Project Overview 
This project is a comprehensive analysis of global data related to the Olympics, combining datasets on world population, GDP, and Olympic performance (medals). Through this analysis, we aim to uncover trends and correlations that could provide valuable insight for future Olympic Games. 

## Project Proposal
**Initial Scope**: Our intial scope was to answer the following questions:     
* How population affect total & gold medal?    
* What years did bigger populations do well/fall short?    
* What sports are dominated by bigger countries?     
* Which have a bigger impact population or GDP on total or gold medal counts?       

**Project Scope**: We narrowed our project down to support the data that we were able to find that matched up with the time given to meet our deadline, with presentable, relevant, data that could help the future olypics. We chose to focus on the affect host_cities, world population, and GDP has on total medal count by answering the following questions.        
* Does population have an affect on a countries total olympic medal count?
* Which as a bigger impact on total medal count GDP or World Population?
* 



## Datasets
The analysis is based on five key datasets:    
**world_population.csv**: Contains population data for each country.    
**gdp.csv**: Includes GDP figures for every country.     
**olympic_medals.csv**: Records the medal count for each country in each Olympic event.     
**olympic_analysis.csv**: Details the start and end dates of the Olympics, host country, participating   countries, and the year.      
**Olypmic_Games.csv**: Lists the country, city, and year of the Olympic Games.       

## Installation and Setup
To run this project, you need to have Python installed along with the following libraries:
* pandas
* matplotlib
* numpy
* seaborn
* sklearn

### Installation Steps:
1. Clone the repository to your local machine. 
2. Navigate to the project directory. 
3. Install the required libaries using pip:
* `pip install pandas matplotlib numpy seaborn sklearn`
4. Ensure the CSV files are placed in the `data/` directory. 

## Anlysis Techniques
This project uses the following analytical methods:

| Technique | Description |
| ----------- | ----------- |
| Comparative Bar Chart | A bar chart used to compare the medal counts of countries during the years they hosted the Olympics versus other years. |
| Comparative Analysis | To identify if there is a difference in a host country's medal tally, we compared Japan's medal count from the 2020 Olympics, which Japan hosted, to its total medal tally from the previous four Olympics (2004-2016). |
| Economic Analysis | Use of GDP data to gauge the affect wealthier nations have on Olympic Performance. |
| Time Series Analysis | To identify trends in total medal count over time and how they correlate with various factors such as population and GDP.|




## Key Findings
| Title | Project ScreenShot | Key Finding |
| ----------- | ----------- | ----------- |
| Japan's Medal Performance During 2020 Olympics | <img src="images/analysis/Japans.png" width="300" height="200"> | This chart show Japan's total medal count in the 2020 Olympics, where they performed significantly better than their average in the previous four Olympic Games (2004 - 2016). Hosting the Olympics seems to have provided a noticeable boost in performance, indicating a potential "home advantage".|
| Percentage of Total Medals Won by Host Countries | <img src="images/analysis/percent_total_by_host_countries.png" width="300" height="200"> | This illustrates how host countries historically performs in terms of medal counts. It is evident that in many cases, the host countries tend to win a higher percentage of total medals, especially in earlier years. This trend flucuates and dramatically lessened in recent Olympics. |
| Paragraph | Text |  |
| Paragraph | Text |  |
| Paragraph | Text |  |
| Paragraph | Text |  |
| Paragraph | Text |  |




<img src="images/analysis/Japans.png" width="300" height="200">

#### This chart show Japan's total medal count in the 2020 Olympics, where they performed significantly better than their average in the previous four Olympic Games (2004 - 2016). Hosting the Olympics seems to have provided a noticeable boost in performance, indicating a potential "home advantage". 

<img src="images/analysis/percent_total_by_host_countries.png" width="300" height="200">
<img src="images/analysis/2020_correlation.png" width="300" height="200">
<img src="images/analysis/gdp_correlation.png" width="300" height="200">
<img src="images/analysis/gdp_scatter.png" width="300" height="200">
<img src="images/analysis/growth_rate.png" width="300" height="200">

## Conclusion

## Future Work
* A more granular analysis of individual sports and countries that typically dominate a particular sport. 
* Incoporating additional datasets like education levels, or healthcare metrics. 
* Pedictive modeling to forecast future Olympic performances. 
# Licensing & Usage
The project falls under the CC0 1.0 UNIVERSAL, no rights reserved. Feel free to use, modify, distribute, or build upon the work for any purpose, without asking permission or providing attribution to us as creators ⭐️
## References
[Xpert Learning Assistant] - Assisted in debugging and cleaning code.    
[BCS Slack Tutor] - Organization and Planning    

### Datasets
[GDP]    
[Olympic Analysis](https://www.kaggle.com/datasets/muhammadehsan000/olympic-historical-dataset-1896-2020)    
[Olympic Host](https://www.kaggle.com/datasets/muhammadehsan000/olympic-historical-dataset-1896-2020)     
[Olympic Medals](https://www.kaggle.com/datasets/muhammadehsan000/olympic-historical-dataset-1896-2020)    
[Olympic Games](https://www.kaggle.com/datasets/muhammadehsan000/olympic-historical-dataset-1896-2020)   
[World Population](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset)  
### Resources

