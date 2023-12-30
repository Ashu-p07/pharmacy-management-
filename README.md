# pharmacy-management-System
Description:

A simple and efficient Pharmacy Management System for inventory, Stocks ,Order  and sales management.
Pharmacies are essential component of healthcare in the United States and handle the function of selling medical drugs. Even though the pharmacies do not seem different than any other shop, their functioning is very different due to various laws regarding drugs. 
This repository houses the  documentation for a comprehensive Pharmacy Management System. The system is designed to streamline and automate various tasks within a pharmacy, offering features for inventory management, prescription tracking, and more.
Thus, preparing a Database Management System for a pharmacy not only requires study of how things are handled from a customer or employee point of view but also the relevant laws. With this project, our aim was to develop a comprehensive system that could deal with challenges faced in day to day operation of a modern pharmacy. We studied the relevant laws and prepared a system that complies with the required Federal and State laws.

Features✨:

Inventory Management: Keep track of medications, supplies, and expiry dates.
Prescription Tracking: Manage patient prescriptions, refills, and histories.
User Authentication: Securely control access with role-based authentication.
Sales and Billing: Generate invoices, manage sales, and track financial transactions.
Reporting: Generate reports for sales, inventory, and other key metrics.
User-Friendly Interface: Intuitive design for ease of use.


In this repository we represented ER diagram of pharmacy management  system which shows relationship between two or more  entites 
Web-based ordering systems. Often provided by drug wholesalers, these systems allow pharmacists to order medications on a wholesaler’s website.
Perpetual inventory systems. The use of perpetual systems (digital or not) is required by federal law for Schedule II controlled substances, and involves recording the quantity of medications continuously as the prescription is filled and dispensed. This way, the medication is automatically removed from inventory and you always have updated stock information.
Automatic dispensing systems. These are machines that automatically count and dispense pills for a pharmacist. Some complex systems even print the label apply it to the bottle.
Web-based ordering systems. Often provided by drug wholesalers, these systems allow pharmacists to order medications on a wholesaler’s website.
Perpetual inventory systems. The use of perpetual systems (digital or not) is required by federal law for Schedule II controlled substances, and involves recording the quantity of medications continuously as the prescription is filled and dispensed. This way, the medication is automatically removed from inventory and you always have updated stock information.



Relation & roles of entities:

A single customer can have multiple orders. Thus, the relation between them is one to many.
There can be variety of drugs which could produce different medicine, so we can say that this is a many to many relation.
A single medicine can be made or produced by different brands, thus this implies one to many relation.
A single login may require different permissions which implies one to many relation.
A single order can contain multiple drugs, thus relationship is one to many. One order, however, can generate only one bill. Thus, the relation between bill and order is one to one.
In medicine table (stock), drug name and batch number can uniquely identify every drug we have in inventory. Batch number is assumed to be unique among manufacturers.
A single brand could have many distributor based on area, as a single distributor cannot supply medicine to all areas of requirements. Therefore, this is also a one to many relation.
Order has order details which comes from stock details thus this is a one to one relation.

Real life Advantage and dis-Advantage:
Improving pharmacists efficiency. Pharmacists spend most of their working hours dispensing drugs. This task requires lots of concentration, a great deal of verification, drug interaction checking, not to mention making sense of the doctor’s handwriting.

Improving patient health outcomes. Patients are seeking counseling from pharmacists and a PMS can directly or indirectly help them get better counseling. Apart from spending more time with a customer in person, pharmacists can communicate with them online on patient portal. And by setting up a connection to a hospital’s EHR, a pharmacist can access a patient’s medication history to make better recommendations.

Preventing medicine fraud. Pharmacies play a pivotal role in helping manage the distribution of controlled dangerous substances (CDSs) by entering all prescription information in the Prescription Drug Monitoring Program database and checking it when dispensing drugs. A pharmacy management system integrated with the PDMP portal allows you to cut down logging time and effort to just a few clicks as information is automatically added to the patient’s history.








