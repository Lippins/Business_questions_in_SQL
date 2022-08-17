# Answering Business Questions with SQL
## Overview
As Business Analysts, we have been contacted by a fictional online music store called Chinook. The company wants our help with answering some business questions.

They provided access to their [database](https://github.com/lerocha/chinook-database), which contains information about the artists, songs, and albums from the music store. Employee information, customer information, and the details of purchase transactions can also be found in the database. The entity relationship diagram below provides a structural overview of the Chinook database:

<img src='https://s3.amazonaws.com/dq-content/189/chinook-schema.svg'
     height = 500
     width = 500/>

## Business Questions
The company needs us to provide insights that help them answer four questions:
- Which albums should they purchase for the US market?
- How are their sales representatives performing?
- In what countries should they run marketing campaigns?
- Should they remove album sales from their business model?

## Analysis Workflow
We queried the database with SQL to answer each business question. The results were passed into a pandas dataframe for visualization with python.

## Insights and Recommendations
- Regarding record labels, the company should make the best out of genres with high popularity in the US. They should select Hip-Hop, Punk, and Pop from their current options. Chinook should also be on the lookout for Rock songs since they account for the USA's most significant sales (53%).

- Jane Peacock is Chinook's best-performing salesperson in total and average sales per customer.

- US and Canada have the most extensive customer base, but customers spend less per transaction. The Czech Republic, India, and Portugal have the highest spending customers. Chinook could launch a marketing campaign to increase the customer base in the three countries.

- While focusing on track sales alone may sound viable, it risks losing revenue from customers who prefer entire albums. It is better to conduct surveys and gather customer perspectives before implementing any new plan.