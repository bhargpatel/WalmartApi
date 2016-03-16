# Project  WalmartApi
------------------------
Object of the Oroject ::
------------------------
This project is regarding Walmart product search API implementations. User will enter the product name and get the result.
In result will get the first product from the search and ten recommendations for that projecr

-------------------------------
Instructions to run the project:
--------------------------------
In other documentations one file WalmartApiApp.jar has attached. 
This file can run from the command line.
command to run that file : #javapath -jar WalmartApiApp.jar

-------------------------
To access the SourceCode :-
-------------------------
Sourcecode will be available in zip bb file.
please unzip it and will be avalabkle in bb\src\search\org
SearchResult.java contains main method and have implementaion in detail.

------------
Assumtions:-
------------
Not main priority of implemetation mechanisms for a front-end GUI or a REST API 
In limited time priority planned to write a simple program but completing all the requirements as mentioned.
In the program used productkey is mine.Not asking for each persons' seperate product key from UI. 

---------------------------------
Functionality and expected output :-
---------------------------------
*Search for products based upon a user-provided search string
Output1. will be first item in the search response as input for a product recommendation search
If not valid product is entered ask for another product to search
Output2. will give the all 10 recommended products with name and ID. It will be sorted based on statistics of 
        average rating of that product
        If Statastics not avalable then will give the appropriate message.

*Getting recommendation output time consuption will be differ based on user's pc and internet performance. 
