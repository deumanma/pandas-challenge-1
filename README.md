# pandas-challenge-1

This challenge was focused on data analysis using Python's Pandas Library. It focused on understanding the data that is presented, what is the shape of the data, and adding additional information based on what is in the dataset. Finally analyzing and summarizing the findings. 

This was a particularly challenging homework as the Pandas information was covered over a long period of time, and as a beginner it was hard to understand what method was appropriate in one instance. 

Started by downloading the starter file and creating a github repository. Then opened the starter code in Jupyter Notebook. The first thing was exploring the data i used the .describe and .dtype commands to better understand what the overall shape was and to try and prevent errors further down in the analysis. 

**Transforming the data**

Started by creating a Subtotal column and adding it to a new data frame that took in the qty and unit price information to and multiplied the unit price by the qty and the output was the value for the subtotal column. Then calculated the shipping price by defining a custom function with the specificed instructions and cost based on weight and added that to a new column called shipping cost. Adding in the salestax and calculating the sales tax and price into a total cost line. Finally calculating the profit and adding it to the table. 

**Confirming the data** 

I concantinated my new dataframe that i made with all the custom calculated columns and merged it to my previous clean_df from the start to include all of the data from the customer and be able to confirm the OrderID and ClientID. I had some trouble with confirming the top clients and my totals were not matching the expected output, but i needed to re-run my previous dataframes after changing a small thing. 
