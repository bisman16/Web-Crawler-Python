# Web-Crawler-Python
This program crawls the first page of the Data Science courses available at GWU - https://my.gwu.edu/mod/pws/courses.cfm?campId=1&termId=201903&subjId=DNSC

Using Beautiful Soup library and requests method, we can scrape all the html content. Then, we can use soup's findAll method to find the 'tr' (table row) attribute and extract contents from each row in the table. We can write all the cells into a csv file and then use it to load data into a pandas dataframe and do data exploration. For example, we can see the number of 1.5 credits and 3 credits Data Science courses available by plotting it.

[![7.png](https://i.postimg.cc/PJL2mZGV/7.png)](https://postimg.cc/q6TsrNv2)

