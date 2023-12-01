# pandas-challenge-1

This challenge was focused on data analysis using Python's Pandas Library. It focused on understanding the data that is presented, what is the shape of the data, and adding additional information based on what is in the dataset. Finally analyzing and summarizing the findings. 

This was a particularly challenging homework as the Pandas information was covered over a long period of time, and as a beginner it was hard to understand what method was appropriate in one instance. 

Started by downloading the starter file and creating a github repository. Then opened the starter code in Jupyter Notebook. The first thing was exploring the data i used the .describe and .dtype commands to better understand what the overall shape was and to try and prevent errors further down in the analysis. 

**Transforming the data**

Started by creating a Subtotal column and adding it to a new data frame that took in the qty and unit price information to and multiplied the unit price by the qty and the output was the value for the subtotal column. Then calculated the shipping price by defining a custom function with the specificed instructions and cost based on weight and added that to a new column called shipping cost. Adding in the salestax and calculating the sales tax and price into a total cost line. Finally calculating the profit and adding it to the table. 

**Confirming the data** 

I concantinated my new dataframe that i made with all the custom calculated columns and merged it to my previous clean_df from the start to include all of the data from the customer and be able to confirm the OrderID and ClientID. I had some trouble with confirming the top clients and my totals were not matching the expected output, but i needed to re-run my previous dataframes after changing a small thing. I also had to concatenate my two data frames and then go back and add suffixes to the columns because i discovered a dupe in the columns that was messing up my code. 

All of the confirmations were accurate until the last table, but when looking back at my calculations they were all running correctly and returning the correct values. I truly don't know what is causing that issue on the final lines. 

**Resources Used**

I used google to find out out to concatenate and add a suffix and also i used ChatGPT to debug some of the error codes that I couldn't immediately figure out. Overall this was a lot harder than i thought it would be. It helped some of the pandas concepts we learned sync in. 
