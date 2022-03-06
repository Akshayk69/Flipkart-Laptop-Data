# Flipkart-Laptop-Data
Data Scrapping from url='https://www.flipkart.com/laptops/pr?sid=6bo%2Cb5g&amp;fm=neo%2Fmerchandising&amp;iid=M_8b3b3f65-7ceb-4375-912c-d2bcdde87c58_1_372UD5BXDFYS_MC.34WHNYFH5V2Y&amp;otracker1=hp_rich_navigation_PINNED_neo%2Fmerchandising_NA_NAV_EXPANDABLE_navigationCard_cc_13_L1_view-all&amp;cid=34WHNYFH5V2Y&amp;p%5B%5D=facets.brand%255B%255D%3DAPPLE&amp;otracker=clp_metro_expandable_6_26.metroExpandable.METRO_EXPANDABLE_Apple_laptops-store_SKIHMOPFPDC3_wp9&amp;fm=neo%2Fmerchandising&amp;iid=M_b4d0e2ef-aaac-4e7e-9272-9b8be53c2dc5_26.SKIHMOPFPDC3&amp;ppt=clp&amp;ppn=laptops-store&amp;ssid=j5fwd6niaz0hnchs1645514684273&amp;page=1'
# Data of apple macbook price,views,ratings etc.
# Procedure:-
The url has html block for each laptop info.

Used selenium to take remote control of Firefox Browser.

Used BeautifulSoup i.e bs4 library to extract data from html tags.

I considerd each block as one and extracted information from it then used list comprehension to get data of all blocks.

After that used for loop and format() function to get data from next pages.

Faced some difficulties while extracting ratings and reviews but solved that using splitting the string and then indexing.

Creating functions to extract multiple data and creating dataframe.

Finally,converted the DataFrame to a .csv file.

Changing the data type of columns as required for future analysis.

Data shape is (48, 6).
