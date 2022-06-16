# RoSa Proj1

# RoSa-Robotic Shopping Assistant
- RoSa is a robotic shopping assistant that is utilized to help automate your shopping buisness. RoSa helps you shop for all your customers from a online vendor called PEGA. It provides customers individual expense reports that is sent through email, as well as produces a final profit report based soley from the shopping that was performed. The profit report contains the 20% commissions from selling for PEGA, it is seperated out for each customer and it is also emailed to the shopper at the end of the shopping trip. 

## Technologies Used
- UiPath Studio 2020.10.7
- Azure Data Studio
- Pega Training Website <https://training.openspan.com/login>

## Features
- Takes in customer shopping lists from excel files
- Shops for custoemrs orders in Pega online platform
- Uses Azure database to collect customer information for each customer
- Records all expenses including base service fee and commission fee in a reciept as a excel file and emails that to the customer
- Produces and emails final profit reports to shopper

## Improvements
- Retrieve customers weekly shopping lists through email in a excel sheet, place that order in Pega and record the expenses in the database
- Have individual orders stored within the database

## Getting Started
- Git clone https://github.com/CynnethaB/Proj1.git
- Open PegaFinal and select customer 1005 xaml
- Edit the "Connect to Database" and "Run Query" UiPath activities to connect to customer Azure Database
- Ensure that customers information is stored in the tables with the correlating information: ([CustomerId], [first_name], [last_name], [street_address], [zip_code], [email], [credit_card_type], [credit_card_number], [credit_card_expiration], [cvv]) 
 - edit customers shopping lists in database

## Usage
- Open PegaFinal.Xaml with UiPath Studio
- Under the Debug File command, select Run File
<img width="231" alt="Screen Shot 2022-06-16 at 12 48 53 PM" src="https://user-images.githubusercontent.com/104387174/174124591-e93c74c3-c3c6-4968-b616-ac702e3c5b61.png">

## Licenses
- This project uses the following license: MIT License
