# Answering Business Questions with SQL
## Overview
As Business Analysts, we have been contacted by a fictional online music store called Chinook. The company wants our help with answering some business questions.

They provided access to their [database](https://github.com/lerocha/chinook-database), which contains information about the artists, songs, and albums from the music store. Employee information, customer information, and the details of purchase transactions can also be found in the database. The entity relationship diagram below provides a structural overview of the Chinook database:

<img src='https://s3.amazonaws.com/dq-content/189/chinook-schema.svg'
     height = 500
     width = 500/>

## Business Questions
The company needs us to provide insights that help them answer four questions:
- Which albums should we purchase for the US market?
- How are our sales representatives performing?
- In what countries should we run marketing campaigns?
- Should we remove album sales from our business model?

## Analysis Workflow
To answer each business question, the database was queried with SQL. The results were then passed into a pandas dataframe for visualization with python.

## Insights and Recommendations
Regarding record labels, the company should make the best out of genres with high popularity in the US. They should select Hip-Hop, Punk, and Pop from their current options. Chinook should also be on the lookout for Rock songs. They account for the most significant amount (53%) of sales in the USA.

Jane Peacock is Chinook's best-performing salesperson both in total and average sales per customer.

US and Canada have the most extensive customer base. However, customers spend less per transaction. The Czech Republic, India, and Portugal have high spending customers. Chinook could launch a marketing campaign to increase the customer base in the three regions.

The plan to focus only on popular tracks may sound viable. However, it risks losing revenue from customers who prefer entire albums. It is better to conduct surveys and gather customer perspectives before implementing the new plan.



