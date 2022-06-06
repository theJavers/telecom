# telecom

Group mini project
Use Spring JPA to model the data in the prompt below.

Suppose you are working for a telecom company. The data requirements of the organization are outlined below.

The telecom company has multiple Plans. Each Plan has a number maximum number of call minutes, a maximum number of text messages, a monthly rate (this is the monthly cost), a long-distance rate, a fee for every 60 minutes of call time above the maximum allowed, and a fee for every 100 text messages above the maximum allowed.
There are 3 types of plans: PayAsYouGoPlan, StandardContractPlan, PremiumContractPlan.
The StandardContractPlan and PremiumContractPlan both have a maximum amount of data usage and a fee for every additional GB of data above the maximum allowed.
The PremiumContractPlan has a long-distance rate of zero.
The telecom company has Users. Users have a name, shipping Address, billing Address, primary phone number, and a list of Accounts.
Address has streetAddress, city, country, and postalCode.
The company requires a table of valid Postal Codes that can be used to verify any newly input postalCode.
Accounts have a status (ACTIVE, DELINQUENT, CANCELLED), a map of Users and their phone numbers (this may be a single User or multiple Users in the case of a family-style plan), a primary User, and a Plan.
The telecom company must be able to query the database to find:

Users by name
Users by phoneNumber
Accounts by User primary phone number
A count of all users with a certain type of plan
You must have adequate test coverage You must use the Money class for all monetary values

It can be helpful to begin by building diagrams.
