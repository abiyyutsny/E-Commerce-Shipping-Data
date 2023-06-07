# E-Commerce-Shipping-Data
Exploratory Data Analysis
Descriptive Statistics
The column "Reached.on.Time_Y.N" should have a data type of object (boolean) because the variable represents categorical data where the value 1 means "no" and the value 0 means "yes."

There are no columns with missing values. It can be observed from the above output that all columns have the same number of rows as the data, which is 10,999 rows.

Columns with unusual summaries:

The "Weight in gms" column has a significant difference between the mean and median values, which is 515. This indicates that the variable has outliers.
The "Mode_of_Shipment" column has a skewed distribution because the category "Ship" dominates, making this feature less useful for classification.
The "Discount_offered" column has a notable difference between the mean and median values, which is 9. This suggests that the variable has outliers. Additionally, considering the range from a minimum of 1 to a maximum of 65, the average is only 13.

Univariate Analysis
Warehouse Block: The distribution of orders in blocks A, B, C, and D is relatively even, while block F has a significantly larger number of orders, reaching approximately twice the number of orders compared to other blocks.

Mode of Shipment: The modes of shipment using air and road transportation have similar numbers, while the mode of shipment using sea transportation has a much larger number, approximately four times higher than the other modes of shipment.

Approximately 68% of delivery delays are caused by using ships as the mode of shipment. Therefore, alternative options such as air and road services can be considered to reduce delivery delays.

The percentage of higher delayed shipments is recorded in Warehouse Block F, amounting to 33%.

Customer ratings have a similar distribution. Almost 20% of total shipments receive a rating of 5.

Product Importance: Low importance and medium importance are the majority, while high importance is the minority.

Gender: Both classes are balanced.

Customer Care Calls: The distribution is positively skewed with a mode of 4.

Customer Rating: Uniform distribution.

Prior Purchases: Positively skewed with a mode of 3.

Discount Offered: Separated into two uniform distributions: 0 to 10 is the majority, and then values greater than 10 up to 65 are the minority.

Weight in gms: Divided into 3 ranges: high from 1000 to 2000 and from 4000 to 6000, low from 2000 to 4000.

Multivariate Analysis
An interesting insight is that the discount offered and the on-time delivery of goods are correlated. The larger the discount offered, the higher the likelihood of the goods not being delivered on time.

The cost of the product and customer care calls are correlated. If customers pay more for the product, they tend to make more customer care calls.

Business Insight
The data shows that 59.67% of orders were not reached on time, while 40.33% of the orders were reached on time.

Many orders were late in the weight range of 2000 - 4000 grams. Most orders that did not reach on time had a weight in the range of 1250 - 4000 grams, where the proportion of orders that did not reach on time exceeded 90% compared to orders that reached on time.

100% of orders with a discount above 10% were late. This indicates a correlation between the offered discount and the on-time delivery of orders. This may occur because the number of orders coming to the warehouse increases significantly during the discount season.
