# Exploring customer insights

## Your mission
You have two different sets of contact details provided to you. One from the contact center team and the other from the waste management department. In real life the major problem is that the two departments arn't talking from the same view.

This means that when a person calls and makes a complaint if it needs to be passed through to waste management, waste management are missing some of the golden information that the contact centre has.

With that brief intro this is the challenge:
* Import the three datasets.
* Join the SuburbtoLGAs dataset with the Contact Center dataset to bring in LGAS for the suburbs.
* Fix the misspelling of New Zeland in the Contact Center dataset.
* Trial merging the two datasets together using the fields (name, email, phone number).
* Change your conditions to finalise your merge so that you result with 100 customers.
* Enrich your merged dataset with demographic information.

At the end you need to figure out a way that the two teams can now use this beautifully single customer view, maybe a power bi report?

### Setting up

#### Activate your trial
Head to the link below and activate a trial
https://go.microsoft.com/fwlink/?LinkId=2083350&clcid=0x409

Alternatively head to https://dynamics.microsoft.com/en-us/get-started/?appname=customerinsights and find the sign up for a free trial link. 


#### Getting data in

##### Creating a data source

Once in Customer Insights go to the **Data** segment of the left hand side menu. Go to **Data sources**. Follow the prompts to add a new data source.

You might be asked whether to **import data** or connect to a **common data model folder**. Choose **import data** as the data source you'll use is **Azure Blobs** 

Name the datasource: **Training Zone** 
> The datasource's name should represent the business name that people would know for the system. 

When prompted for the connection details of the blob storage, put in below

Ensure to switch the **authentication kind** to **account key**.

__account name__: trainingzonedatasets

## Now hack away

Okay so now it's upto you to complete the challenge.


