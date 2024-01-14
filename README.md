# Data Model Mapping POC
This is a POC to achieve multiple data modeling soucing from different end customers/users/entities/organizations and organize data in a way that is suitable for the destination entities. We have the below entities

# Destination Entities
- Ebay
- Amazon
- Google
  

Google, Ebay and Amazon provide API's to import the products/catalogues. 

AMAZON Marketplace API's
https://docs.developer.amazonservices.com/en_US/dev_guide/DG_IfNew.html

Ebay Marketplace API's
https://developer.ebay.com/develop/apis

Google Merchant Data Feed
https://support.google.com/merchants/answer/7439058?hl=en-GB


# Problem statement
The problem statement is that we receieve the data feeds from different sources and in a different formats. The formats can be CSV, Xlsx etc We need to train our system to map those feeds to suits the requirements of our destination entities.

![Screenshot (624)](https://www.nembol.com/wp-content/uploads/2023/01/import-from-csv.png)
