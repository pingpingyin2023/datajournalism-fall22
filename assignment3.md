# Assignment 3
### *By Pingping Yin*  
I think there are several items below for the dataset we selected for our final project that should be paid close attention to in case the bad data contaminates our analysis.  
Take the Syracuse University’s [Transactional Records Access Clearinghouse](https://trac.syr.edu/immigration/detentionstats/facilities.htm) for example.  
## 1.Values are missing  
Many detention facilities' **Current Guaranteed Minimum** column are left blank. Does it mean that the data for these detention facilities were not collected? We should figure out why the information is missing. We should ask the source what the absence of this value means.  
## 2.Zeros replace missing values  
Some detention facilities' **Average Daily Population** are showing the number "0". We need to be cautious that does it mean there is no one there, or they did not collect the data and just arbitrarily used “0” instead. We should also ask the source to make sure.
## 3.Name order is inconsistent  
The ordering of detention facilities' names is confusing. For the latest two months, September and August,2022, they are following an alphabet order, but the name order of months before are randomly.  
## 4.Data are too granular  
We want a state level data, but the dataset was set by county. Fortunately, we could aggregate the data by using the Pivot Table feature of Excel or Google Docs, by using a SQL database or by writing custom code. 
