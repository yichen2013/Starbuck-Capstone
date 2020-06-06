# Starbuck-Capstone


## Table of contents
* [Introduction](#Introduction)
* [Technologies](#Technologies)
* [File Descriptions](#FileDescriptions)
* [Results](#Results)

## Introduction

In this project, I preprocessed the consumer behavior data on Starbucks rewards mobile app. I used this data to help Starbucks decide the marketing strategies. 

The record of transactions, offers received, offers viewed, and offers completed are not organized based on offers. I merged the transactions, offers received, offers viewed, and offers completed based on the offer_id, users, and the timestamp that the event happened. The demographic data and offer description data are all merged into the transcript data.
I visualized the offer completed situation based on the demographic data and offer description data.

Machine learning models also are built to provide marketing strategies on the individual level, i.e. given the demographic data of a consumer, my model can give suggestions about which offer should send to him/her.



## Technologies
* Python version 3.6.

The packages I used:
* matplotlib
* sklearn
	
## File Descriptions

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed
* Starbucks 
 
## Results
 
General marketing strategies:
* No informational offer.
* Send more offer to older people.
* Send more offer to female.
* Send more offer to rich people.
* Send more offer to customers who became member between 2015 and 2017.
* Use social media as the main channel to send out offer. 
* No need to send out offer 6 and 7, since none of them is finished by the customers.
