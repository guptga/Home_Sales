# Big Data- Home_Sales Analysis 

![Image](https://www.artezio.com/wp-content/uploads/2019/11/shutterstock_1440847499_0.jpg)

## Big Data Defined

The definition of big data is data that contains greater variety, arriving in increasing volumes and with more velocity. This is also known as the three Vs. Put simply, big data is larger, more complex data sets, especially from new data sources.


## Apache Spark defined

Apache Spark is a data processing framework that can quickly perform processing tasks on very large data sets, and can also distribute data processing tasks across multiple computers, either on its own or in tandem with other distributed computing tools. These two qualities are key to the worlds of big data and machine learning, which require the marshaling of massive computing power to crunch through large data stores. Spark also takes some of the programming burdens of these tasks off the shoulders of developers with an easy-to-use API that abstracts away much of the grunt work of distributed computing and big data processing.


## Case Study

### Methodology

Using SparkSQL, we read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

* Created a temporary table called home_sales.

* Answered the following questions using SparkSQL:


* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://user-images.githubusercontent.com/116124534/231249399-df421054-12a5-4fdf-95bc-124afe05a24c.png)

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://user-images.githubusercontent.com/116124534/231249578-877bfa4b-e515-4705-bed0-125618ddeadf.png)


* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://user-images.githubusercontent.com/116124534/231249767-3e6cedf2-da8f-47e4-874b-1e42f247bd10.png)

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![image](https://user-images.githubusercontent.com/116124534/231250028-dd7fd42a-d8b7-4fd4-945f-a04b9a093ebf.png)


