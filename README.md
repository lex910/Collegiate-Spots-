# Collegiate-Spots-
Ongoing Project Exploring Collegiate Sports Data 

## Business Objectives: 
This project aims to uncover trends in a mock dataset for collegiate sports data. Using three different tables, ticket data, donor data, and email data, a comprehensive data analysis project will provide insights on customer types and sports that are driving the most revenue generation, ticket price levels to advertise to different customer segments, a comprehensive analysis of donor trends, and the performance of email campaigns. 

## Methods
Using the three datasets, Machine Learning Methods will be used to create customer segmentations based on purchasing habits, and models to predict future behaviors and interaction. Tableau will be used to create analytical dasboards to display findings in the data. 

## Data Dictionary 
** It is important to note that the data used to complete ths project is mock data and completely randomly generated resulting in some infeasible solutions. All methods are used properly, conclusions may just not make complete sense based on the generated data. For example some sales dates are after purchase date, meaning people purchased after the event happened. 

#### Table 1- Ticket Data 
CustomerID 
Name 
SeasonCode: Specific code of referencing sport and season year
SeasonName: Sport followed by season year 
ItemCode: Code associated with purchased item 
ItemName: School ticket is associated with 
SaleDate: Date that the ticket was purchased
EventDate: Date that the event took place 
PriceLevel: Number associated with the price of the ticket 1 being the most expensive→10 being least(student section) 
PriceLevelName: Specific name of seating section (names differ for sports) 
ItemPrice: Price of a single item ticket 
Quantity: The number of tickets purchased
OrderAmount: Total order balance 
PaidAmount: Amount paid for tickets 

#### Table 2- Donor Data 
DonorID: Unique ID given to each donor
Donorname: First and last name of the donor
RecievedDate: Date the donation from the donor was recieved
Fiscal Year: year donation was made 
Allocation Name: Division that donation was given to  
TotalPaymentAmount: Amount donated up front  
TotalPedgeAmount: Amount promised to pay in the future  
ZipCode
City 
State
County 
FundRep: Representative of the fund that the donation was made to

#### Table 3- Email Metrics 
EmailID: Unique identifier for each email campaign
RecipientEmail: email adress of the recipient
EmailType: Specific event that the email relates to 
SentDate: day email was sent
Opens: Total number of times that the email was opened 
Clicks
DistinctOpens 
DistinctClicks

## Dashboards 

![Ticket Sales Dasboard](https://github.com/user-attachments/assets/94b3c1ef-e792-4efd-a07d-c540be61c816)
