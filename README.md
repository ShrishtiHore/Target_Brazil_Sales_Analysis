# Target_Brazil_Sales_Analysis

Target is one of the world’s most recognized brands and one of America’s leading retailers.This business case has information of 100k orders from 2016 to 2018 made at Target in Brazil. Its features allows viewing an order from multiple dimensions.

Data is available in 8 csv files:

1. customers.csv
2. geolocation.csv
3. order_items.csv
4. payments.csv
5. reviews.csv
6. orders.csv
7. products.csv
8. sellers.csv

Each feature or columns of different CSV files are described below:
The customers.csv contain following features:
customer_id : Id of the consumer who made the purchase.
customer_unique_id :Unique Id of the consumer.
customer_zip_code_prefix : Zip Code of the location of the - consumer.
customer_city : Name of the City from where order is made.
customer_state :State Code from where order is made(Ex- sao paulo-SP).
The sellers.csv contains following features:
seller_id : Unique Id of the seller registered
seller_zip_code_prefix : Zip Code of the location of the seller.
seller_city : Name of the City of the seller.
seller_state : State Code (Ex- sao paulo-SP)
The order_items.csv contain following features:
order_id: A unique id of order made by the consumers.
order_item_id: A Unique id given to each item ordered in the order.
product_id: A unique id given to each product available on the site.
seller_id: Unique Id of the seller registered in Target.
shipping_limit_date: The date before which shipping of the ordered product must be completed.
price: Actual price of the products ordered .
freight_value: Price rate at which a product is delivered from one point to another.
The geolocations.csv contain following features:
geolocation_zip_code_prefix: first 5 digits of zip code
geolocation_lat: latitude
geolocation_lng: longitude
geolocation_city: city name
geolocation_state: state
The payments.csv contain following features:
order_id: A unique id of order made by the consumers.
payment_sequential: sequences of the payments made in case of EMI.
payment_type: mode of payment used.(Ex-Credit Card)
payment_installments: number of installments in case of EMI purchase.
payment_value: Total amount paid for the purchase order.
The orders.csv contain following features:
order_id: A unique id of order made by the consumers.
customer_id :Id of the consumer who made the purchase.
order_status: status of the order made i.e delivered, shipped etc.
order_purchase_timestamp: Timestamp of the purchase.
order_delivered_carrier_date :delivery date at which carrier made the delivery.
order_delivered_customer_date: date at which customer got the product.
order_estimated_delivery_date: estimated delivery date of the products.
The reviews.csv contain following features:
review_id: Id of the review given on the product ordered by the order id.
order_id: A unique id of order made by the consumers.
review_score :review score given by the customer for each order on the scale of 1–5.
review_comment_title: Title of the review
review_comment_message: Review comments posted by the consumer for each order.
review_creation_date :Timestamp of the review when it is created.
review_answer_timestamp: Timestamp of the review answered.
The products.csv contain following features:
product_id: A unique identifier for the proposed project.
product_category_name: Name of the product category
product_name_lenght: length of the string which specifies the name given to the products ordered.
product_description_lenght: length of the description written for each product ordered on the site.
product_photos_qty :Number of photos of each product ordered available on the shopping portal.
product_weight_g :Weight of the products ordered in grams.
product_length_cm: Length of the products ordered in centimeters.
product_height_cm: Height of the products ordered in centimeters.
product_width_cm: width of the product ordered in centimeters.

Insights and Recommendations :

- We have 99,441 customers of data available.

- We have 96096 number of Unique Customers ids.

- 14994 different locations of customers

- Customers are from different 4119 cities and 27 states from Brazil.

- total 99441 customers are there in given data.

- from total 99441 orders , 1107 are shipped ,625 were canceled, 96478 are delivered.

- 68% customers are from southeast Brazil , 14% are from south Brazil and rest are other other regions of Brazil .

- Total 3095 sellers who are from 611 different cities and 23 states in Brazil and from 2246 different areas as per zip-code data.

- São Paulo state has the highest numbers of sellers in country.

- Analysis of sales and revenue as per time :

- Time period for which the data is given is 25 months.

- compare to 2017 , revenue has increased in 2018 by 21%.

- Average number of order are higher during November month , september and october month average orders are comparatively low , in may and july and august have higher average orders compare to other months.

- Tuesday, monday and wednesdays have relatively higher number of orders.

Increasing trend :

- there is a increasing trend in orders , trend sustains during 2018. There a slight fall we can observe during october 2017 following with a great hike in november month and again a fall in end of december 2017 and january 2018.

- we can observe the trend of increasing orders with time and also for revenue.

- we can observe there's 815% growth increased in terms of orders and 707% growth increment in terms of revenue in January from 2017 to 2018.

- growth rate for july and august in 2017 to 2018 is relatively very low!

- 2017-february, 2017-march,2017-november were the highest growing sale month compare to its previous month.

In products Data , total 32951 different products available in Target with 73 different product_category.
health and beauty, Watches present, bed table bath, sport leisure, computer accessories, Furniture Decoration, housewares, Automotive are some of the top selling product categories.

health and beauty products are top selling having highest orders.

PCs and Musical Instruments category have relatively less number of products , but contributes in a high revenue.

PCs,house pastals oven and cafe,agro industry and commerce,musical instruments,Kitchen portable and food coach are having highest average product price categories.
61% orders are between price range 10-100. 33% are from 101-500 price range.

PCs/electronics, Furniture products,Kitchen Service Area Dinner and Garden equipments, Industry Commerce and Business , agro indsustrial commercial products,Bags Accessories, musical instruments, Construction Tools Illumination are some product categories having high average freighter value.

Delivery time :

- avg_estimated_delivery_time and delivery_time have a positive correlation with avg_freight_value.
- after purchasing , the average time for approving the order by seller is 0.26 days and median time is 0 , means with in a day.
- average time taken for a carrier to start the delivery is 2 and a half day.
- average time taken to complete delivery is 12 days. and median of delivery time is 10 days.
- estimated time delivery average is 23 days.

- There is a positive correlation between freight value and delivery time.

- states São Paulo ,Paraná, Minas Gerais, Distrito Federal ,Santa Catarina and Rio de Janeiro are some of the states having faster delivery time relatively.

- Alagoas, Amazonas, Amapá ,Pará and Roraima are some states have very slow delivery time relatively.

Region and State vise Analysis :

- São Paulo ,Rio de Janeiro , Minas Gerais ,Rio Grande do Sul and Paraná are top 5 highest orders states and also generating highest revenue.
more than 80% of orders are coming from south, southeast and nothest Brazil. 90% of the revenue is coming from south, southeast and nothest Brazil .

Recommendations :

- from the distribution and statistical analysis we can observe the average time to complete the delivery is 12 days . which should be reduced to atleast half , as due to high competition in e-commerce market , its is vital to do so.

- In order to reduce the delivery time, if we look at the average time for carrier to start the delivery itself takes atleast 2 and a half days. and order approaval time is 0.26 days . These two should be optimized at as low as possible, that can result into delivering faster.

- If we look at Top states where delivery is really slow compared to estimated date , they are all from north Brazil region. Delivering faster in the north states may create and increase new customers and revenue from north.

- Increasing network in north brazil , having small towns can help increase the customer base. As north Brazil has the worlds largest river and most extesive rain forest, must be a good travel destination, introducing necessary survival/ camping/adventure products can help increase revenue and order from northen region .
top selling items are between 10-100 dollars,introducing new different more products from top selling categories can increase revenue more.

- It was observed an increasing trend in revenue and orders over time , yet during october and january sales are decreasing probably after Festival Sales. Introducing possible discount on not so running product can help sell more products during those low going months.
