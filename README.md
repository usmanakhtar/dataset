

# Dataset for the Assignmnent 

This is the assigment dataset for the MS data analytics student. This dataset contains information about Zenith Insurance, a dynamic insurance provider known for its innovative approach, utilizes various outreach methods to promote its term life insurance products. This repository contains a dataset on past telemarketing campaigns conducted to promote insurance subscriptions. The data can be used to build machine learning models that predict customer likelihood to subscribe to the insurance product.

## Dataset Description

The dataset comprises information about customers and their interactions with telemarketing campaigns for insurance products. It includes features related to customer demographics, contact details, campaign history, and the target variable indicating subscription status.

## Features

* **Customer Demographics:**
    * `age` (numeric): Customer's age.
    * `job` (categorical): Customer's type of job.
    * `marital` (categorical): Customer's marital status.
    * `educational_qual` (categorical): Customer's educational qualifications.
* **Contact Details:**
    * `call_type` (categorical): Type of communication used for contacting the customer (e.g., phone call, email).
    * `day` (numeric): Day of the month (numeric) when the last contact was made.
    * `mon` (numeric): Month of the year (numeric) when the last contact was made.
    * `dur` (numeric): Duration of the last contact, in seconds.
    * `num_calls` (numeric): Total number of contacts made with this customer during this campaign.
* **Campaign History:**
    * `prev_outcome` (categorical): Outcome of the previous marketing campaign for this customer (possible values: "unknown", "other", "failure", "success").

## Target Variable

* `y` (categorical): Indicates whether the customer subscribed to the insurance product ("yes" or "no").

## Potential Uses

This dataset can be valuable for various data analysis and machine learning tasks, including:

* **Predicting customer insurance subscription:** Build models to identify customers most likely to subscribe to insurance based on their characteristics and past interactions.
* **Understanding customer behavior:** Analyze how different factors influence customer responses to telemarketing campaigns.
* **Optimizing marketing strategies:** Develop more targeted and effective campaigns by identifying the most successful contact methods and customer segments.


