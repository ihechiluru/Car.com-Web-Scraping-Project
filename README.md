# Car.com-Web-Scraping-Project
This is an open-source web-scraping project, where I used the beautiful soup library in python to extract the following details from the cars.com website: 
Name 
Mileage 
Price  
Rating 
Rating_count 
Dealer Name 
Single page scraping: As regards scraping, I extracted the information above from 20 cars on the first page of the website and then extracted the details above and parsed them into an excel file.  
Multi-page scraping:  For scraping the same details for multiple pages, I have developed a slightly modified crawler that goes through each page (through the first 10 pages), finds the details we need and extracts them into our data frame. 
Here's a Link to find the webpages that were scrape:
https://www.cars.com/shopping/results/?dealer_id=&keyword=&list_price_max=&list_price_min=&makes[]=honda&maximum_distance=20&mileage_max=&page_size=20&sort=best_match_desc&stock_type=all&year_max=&year_min=&zip=

Find the extended ReadMe File for more info. 
