# PRML_course_project_1 report 
NAME – LAKSHIT CHOUBISA
ROLL NO. – B21AI057
PRML MINOR PROJECT
TITLE – CUSTOMER SEGREGATION

TASK - We have to segment customers based on their buying behavior on the market.
Your task is to classify the data into the possible types of customers which the retailer
can encounter.

Steps followed by me :
1) Load the data set.
2) Preprocessing and visualization of data.
3) Making a new dataframe that will contain all information about a customer.
4) Cluster the customers based on type of products they buy (like related to food,
   electronics etc.)
5) Cluster the customers based on all information collected in the new data frame
   except the type of product a customer buy (ie in this case, clustering will be
   independent of description column (product type))
6) Cluster the customer based on their financial behavior and the type of products
   they buy. (in this case we will take into account the description column and use
   text clustering and general clustering concept together to segment customers)
7) Cluster the customers solely based on their financial habits (in this case I will not
   take into account what type of product a customer buy, country, time, how many
   time he/she goes shopping, etc).
