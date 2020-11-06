# Starbucks-Capstone-Challenge
A Exploratory data Analysis Challenge on Starbucks data with customer information and offer details 

### Introduction
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

Your task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. You'll see in the data set that informational offers have a validity period even though these ads are merely providing information about a product; for example, if an informational offer has 7 days of validity, you can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

You'll be given transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.

Keep in mind as well that someone using the app might make a purchase through the app without having received an offer or seen an offer


 
 ## #Libraries used:
 * pandas 
 * numpy
 * matplotlib
 * sklearn
 
 
 
 ### Motivation for the project
 This project was engineered by udacity ,
 This aim of this project is buid a suitable model that predicts whether a customer will complete an offer or not

 ### Files in the repository 
 
 * Starbucks-Capstone.ipynb - a jupyter notebook that contains all the code for this project 
 * data
    * portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
    * profile.json - demographic data for each customer
    * transcript.json - records for transactions, offers received, offers viewed, and offers completed
    * profile.json - a json file that contains data ab
    
 
