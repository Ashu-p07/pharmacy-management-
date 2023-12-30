# pharmacy-management-
A simple and efficient Pharmacy Management System for inventory, Stocks ,Order  and sales management.
Pharmacies are essential component of healthcare in the United States and handle the function of selling medical drugs. Even though the pharmacies do not seem different than any other shop, their functioning is very different due to various laws regarding drugs. 
This repository houses the  documentation for a comprehensive Pharmacy Management System. The system is designed to streamline and automate various tasks within a pharmacy, offering features for inventory management, prescription tracking, and more.
Thus, preparing a Database Management System for a pharmacy not only requires study of how things are handled from a customer or employee point of view but also the relevant laws. With this project, our aim was to develop a comprehensive system that could deal with challenges faced in day to day operation of a modern pharmacy. We studied the relevant laws and prepared a system that complies with the required Federal and State laws.
Features✨
Inventory Management: Keep track of medications, supplies, and expiry dates.
Prescription Tracking: Manage patient prescriptions, refills, and histories.
User Authentication: Securely control access with role-based authentication.
Sales and Billing: Generate invoices, manage sales, and track financial transactions.
Reporting: Generate reports for sales, inventory, and other key metrics.
User-Friendly Interface: Intuitive design for ease of use.

In this repository we represented ER diagram of pharmacy management  system which shows relationship between two or more  entites 

Relation & roles of entities:
A single customer can have multiple orders. Thus, the relation between them is one to many.
There can be variety of drugs which could produce different medicine, so we can say that this is a many to many relation.
A single medicine can be made or produced by different brands, thus this implies one to many relation.
A single login may require different permissions which implies one to many relation.
A single order can contain multiple drugs, thus relationship is one to many. One order, however, can generate only one bill. Thus, the relation between bill and order is one to one.
In medicine table (stock), drug name and batch number can uniquely identify every drug we have in inventory. Batch number is assumed to be unique among manufacturers.
A single brand could have many distributor based on area, as a single distributor cannot supply medicine to all areas of requirements. Therefore, this is also a one to many relation.
Order has order details which comes from stock details thus this is a one to one relation.






