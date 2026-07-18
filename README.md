# Housing-Data-Analysis

# Key Objective
Using London housing data from 1995 - 2020, clean the dataset and perform exploratory data analysis to derive key insights on the housing market.

Insights are provided on the following key areas:

Best Appreciating Areas Since 1995: Areas such as London, Hackney, and Southwark tend to have the greatest YoY appreciation on average.

Recent Years: Since 2016 areas such as Bexley, Havering, and Newham tend to outperform other areas, while areas such as Islington and Westminster perform poorly in terms of YoY appreciation.

Relationship Between Crime and Housing Prices: Areas with lower crime rates tend to be more expensive, but buyers are still willing to pay above average prices in areas with above average crime rates.

# Data Structure & Initial Checks

We are working with a dataset consisting of 13,500+ records. There is some missing data, but this could be due to data not being recorded at the time, so it may not be an error. For something such as the number of crimes committed, we could use average values as placeholders for nulls, but I chose not to do that. The only thing that I did was esnure that data types were actually correct. Year and months have been extracted so they can be utilized to MoM and YoY calculations later on.

# Executive Summary

## Overview of findings

- Average yearly appreciation for homes in London is ~8%
- The average home in London sells for around ~£263k
- City of London, Hackney, Southwark are the top 3 areas in terms of average YoY appreciation since 1995
- Homes in England make up for 40%+ of home sales
- Correlation between crimes and selling price are not as strong as expected

<img width="921" height="516" alt="image" src="https://github.com/user-attachments/assets/66670437-14b5-4704-bd51-fa045a74aa21" />
<img width="924" height="516" alt="image" src="https://github.com/user-attachments/assets/c7e2d9e3-1279-4234-ae26-274c0e936da5" />
<img width="923" height="517" alt="image" src="https://github.com/user-attachments/assets/8f7c53c6-da19-45a6-956d-c734a5b278c2" />

# Insights Deep Dive
### Average YoY Appreciation Ranked:
<img width="926" height="550" alt="image" src="https://github.com/user-attachments/assets/45aa093d-7f25-4ab8-bcc0-33570977a862" />
Average YoY appreciation among all areas is ~7.92%. The City of London is the leading area coming in at an average of 10.14% annual appreciation. The North East is the worst-performing area coming in at an average of 5.13%. Most areas tend to fall between 7-8% YoY appreciation.

### Percentages of Houses Sold by Area:
<img width="923" height="560" alt="image" src="https://github.com/user-attachments/assets/a763ead5-f0fc-4786-beb7-0051baf5d6f4" />
England makes up for over 44% of home sales since 1995 which is far greater than any other area. The area with the second most home sales is the South East at just over 8% of total home sales. The average selling price for a home in England is around £247k, putting it below the average selling price of around £263k.

### Relationship Between Crime Rates and Housing Prices:
<img width="763" height="421" alt="image" src="https://github.com/user-attachments/assets/c530971a-fede-4d7f-ae31-6e3035674b25" />
We would expect home prices to be generally higher in areas with low crime rates and cheaper in areas with high crime rates. The data shows that this is mostly true, but perhaps their relationship isn't as strong as expected. Most homes that sell for greater than £1M tend to have less than 3,000 crimes committed. We can observe that some people are still willing to pay around £1M despite being in an area where 4,000+ crimes are committed. Many cheap homes can be had in areas with low crime rates. The correlation is fairly weak and crime rates may not have as big of an impact on home prices as expected.

# Recommendations:


