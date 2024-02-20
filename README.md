# AdWords-Marketing for TV Screens
📺

The goal of this report is to give insights regarding the set-up of a fictional SEM
marketing campaign. This was done as an assignment for the class "Big Data and Analytics in Marketing"

The aim was to show how an existing company could set-up such a campaign in astructured approach.

## Introduction 
The starting point was a dataset found on the internet (Kaggle) that was applied to the
Indian electronics retailer “Vijay Sales”. Based on there product portfolio Vijay Sales.
The results were four different marketing campaign for four different customer groups
resulting in a potential revenue stream of up to ₹ 147 mn, which is the equivalent to
1.82 mn dollar within four weeks.

## Data 📁
Dataset: https://www.kaggle.com/code/devsubhash/tv-brands-market-analysis-eda

## EDA 👓
Data was visualized with Google Dashboard looker studio

Following questions were answered (answers see report)

1) How are price and size of TV related?
2) How are price and brand related?
3) What role does the operating system of the television play?
4) What roles does the resolution of TV play?
Based on that different product segments were identified

## Grouping 🧑‍🤝‍🧑
Based on the EDA and spending behavior we derive four groups. Each group will
receive later on a dedicated campaign. Even though there are customers for devices in
between those four groups help to simplify a mutual exclusive approach.

1) High endprice/High tech
2) Samsung fans
3) Casual user
4) low price

## Keywords 💻

To find the best keywords based on the attributes of TV screen given so far, Python is
used with the library “advertools”. Each of the 4 groups receives an own table of
keywords including the following elements.
1. Products (list of products)
2. Words that indicate if someone wants to buy or learn
3. Maximum lens tells if words should be combined
4. Campaign name as name of the campaign
5. Match of keyword and entry of customer (phrase, match, build)
6. Keywords as a combination of products and words

The keywords of the table are introduced in the next step within Google Ad Words to
have a first match and iterate on the suggestion of Google Ad Words itself.

## Google Adwords

After keywords have been created Google Ad words was used to create the respective
campaigns. For all the campaigns the goal was to increase the website traffic first.
Potential other actions like sales, leads or brand awareness, other functions of Google
11
Ad Words, were not realized in this stage due to the inexperience of Vijay Sales with
Ad words and the need to test it out first.
Furthermore it was also decided to limit the campaign type to “Search” for the same
reasons.
All campaigns were set between 16th Oct and 16th November which is the month
before Diawli, where most of the user are likely to shop. The display time for group 1
and 2 was limited to the evening 6pm and midnight as they are likely to work longer
than customers from group 3 and 4, who would already receive ads starting at 3 pm.
