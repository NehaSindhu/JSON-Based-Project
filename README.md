# JSON-Based-Project
This repository is having all the codes,files used in Assignment - 1 in Elite Techno groups Internship.

# About
- IMS can be used to add new Products, delete , Modify and view Products added to the Inventory and then storing in the records.json file in json format.
- IMS can be used to Purchase Products, Generate the bill of the Purchase and Transactions file of sales of the day
- learned JSON , NoSQL databases , File Handling , Python loops , time module and much more.

## Files

- Adding Products to inventory.ipynb - To Add Products in Inventory

- Purchasing Products from inventory.ipynb - To Purchase Products from Inventory

- products.json - Records of Products present in inventory generated from 'Adding Products to inventory.ipynb'

- sale.txt - Transactions of Products in Inventory  generated from 'Purchasing Products from inventory.ipynb'


###  Products Features
- Products(Product Id, Products name, Price, Quantiy, Discount )

### Features
- Transactions (Transacion Id, Product Name, Customer Name, Quantity, Amount Paid )

## Features - Add Products to inventory.ipynb

1. Adding new items in inventory
2. Deleting items from the inventory
3. Modifing the items from the inventory as per user requirements
    - Modify all the information added
    - Modifing only price of the Products
    - Modifing only Quantiy of the Products
4. Showing all the Products added or persent in the inventory
    - Showing all the Products
    - Showing specific Product according to Products id
5. Recording all the Products entries and storing in record.json file

## Features - Sell Products from inventory.ipynb

1. Showing all the Products available in the inventory
2. Selling and Generating the Bill of the Transactions
    - Calculating the Discounted Price of the Purchase Products
    - Updating the Quantiy of the Products after Purchase
    - Generating Bill
3. Generating the sales.txt file of all the Transactions on the day
  
## Requirements

- Python 3
- jupyter Notebook
