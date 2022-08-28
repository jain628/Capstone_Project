# Udacity Capstone Challenge
Udacity's Nanodegree Capstone Challenge for Starbucks
# Installation of necessary libraries
  pandas<br>
  numpy<br>
  math<br>
  json<br>
  matplotlib<br>
  seaborn<br>
  sklearn<br>

# Objective of the Project
Using similated data obtained from Starbucks that mimics how customer are influenced by promotional offers. The aim of this project is to create a predictive model to predict whether the combination of user and offer type will result in a successful offer.

# Description of files used in the project
The analysis and predictive models are available in the Jupyter Notebook.
The datasets are a simplified version of the real Starbucks app because the data only contains information regarding one product whereas Starbucks has a whole line of products.
The data given to us was stored in 3 json files:

1. portfolio.json - containing offer ids and data regarding the offer: duration, difficutlty and type.
2. Profile.json data containing demographic information for each customer.
3. transcript.json - data containing every record for transaction, offers recieved, offers reviewed and offers completed.
Here are the schemas for each file:

<b>Portfolio.json</b>

offer_id (string) - offer id
offer type (string) - the type of offer: Informational, Discount, BOGO.
difficulty (int) - minimum required to spend to complete an offer.
reward (int) - the reward is given for completing the offer.
duration (int) - time for the offer to be open in days.
channels (list of strings)

<b>Profile.json</b>

age (int) - age of the user
become_member_on (int) - integer referring to the date the customer created an account.
gender (string) - gender of the customer (Male, Female, Other)
id (str) - customer id
income (float) - customers income

<b>Transcript.json</b>

event (string) - record description (transaction, offer received, offer completed, offer viewed)
person (string) - customer_id
time (int) - time in hours since the start of the test.
value (dictionary containing strings) - contains either offer id, amount or reward depending on the event.
# Results
I have created a medium post about the 5 Things to explore while building an ML model using starbucks data and project as a reference which allows one to explore all verticals before finalizing the model. It can be found <a href="https://medium.com/@jainpranjal4444/5-things-to-explore-while-building-an-ml-model-35ad4b7c4021">here</a>.
# Licensing & Acknowledgement
This project was completed as part of the Udacity Data Scientist Nanodegree.Some concepts and codes are adapted from here:(https://github.com/jdabel123/Udacity-CapstoneProject-Starbucks/blob/main/Starbucks_Capstone_notebook.ipynb). Special thanks to Udacity, Starbucks and the mentioned github source.


