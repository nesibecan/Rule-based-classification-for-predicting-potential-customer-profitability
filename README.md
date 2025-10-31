# Rule-based-classification-for-predicting-potential-customer-profitability

Project Description 
Gezinomi aims to create level-based customer definitions by using certain attributes of its past sales data. Based on these definitions, customer segments will be generated to estimate the potential revenue that new customers may bring to the company.
For instance, the company wants to estimate how much revenue a new customer—who plans to visit an all-inclusive hotel in Antalya during the high season—would potentially generate.

Dataset Story 
The gezinomi_miuul.xlsx dataset contains the prices of sales made by the company Gezinomi, along with various details related to these transactions.
Each record in the dataset represents a single sales transaction, meaning the table is not deduplicated. In other words, a single customer may have made multiple purchases, and therefore may appear in the dataset more than once.

📊 Variables (gezinomi_miuul.xlsx)
•	SaleDate: The date when the sale was made.
•	SaleID : Sale ID
•	Price: The amount paid for the sale.
•	ConceptName: The hotel’s concept information (e.g., all-inclusive, bed & breakfast).
•	SaleCityName: The city where the hotel is located.
•	CheckInDate: The date when the customer checks into the hotel.
•	CInDay: The day of the week on which the customer checks in.
•	SaleCheckInDayDiff: The number of days between the sale date and the check-in date.
•	Season: The season corresponding to the customer’s check-in date.
