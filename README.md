# Data Model Mapping POC
This is a POC to achieve multiple data modeling soucing from different end customers/users/entities/organizations and organize data in a way that is suitable for the destination entities. We have the below entities

# Destination Entities
- Ebay
- Amazon

Both Ebay and Amazon provide API's to import the products/catalogues. 

AMAZON Marketplace API's
https://docs.developer.amazonservices.com/en_US/dev_guide/DG_IfNew.html

Ebay Marketplace API's
https://developer.ebay.com/develop/apis

# Problem statement
The problem statement is that we receieve the data feeds from different sources and in a different format.s The formats can be CSV, Xlsx etc We need to train our system to map those feeds to suits the requirements of Amazon and Ebay Both. 
