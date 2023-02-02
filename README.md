# WebScrapping

This is a repository of the assignment allocated analystt.ai for internship.
The assignment is divided into two parts. Part 1 focuses on gathering information on products listed within the first 20 pages of search results, while Part 2 involves extracting various key details such as the manufacturer, ASIN number, and product description from the 200 products obtained from Part 1.

Part 1 scraps first 20 pages from the search results and stores the information in a file called "productList.json".

Part 2 reads this file and stores first 200 product urls and then scraps information from them individually. Then the information is stored in both "products.json" file for evaluation and "products.csv" format as required.
