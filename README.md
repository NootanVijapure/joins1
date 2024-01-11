# Instructions:

## Create Tables:

## Create two tables: gift_recipients and gifts.
The gift_recipients table should include columns such as recipient_id, recipient_name, and any other relevant information.
The gifts table should include columns like gift_id, gift_name, and gift_category.
Add Data:

Add at least five rows of sample data to each table. Ensure that there is a common column (e.g., recipient_id or gift_id) that can be used for joining.
## Left Outer Join:

Write a query using Left Outer Join to retrieve a list of all gift recipients and the gifts they are receiving for Christmas. Include recipients who are not receiving any gifts.
Provide a brief explanation of the results obtained from the query.
## Right Outer Join:

Write a query using Right Outer Join to display a list of all gifts and the recipients for each gift. Include gifts that have no assigned recipients.
Explain the results obtained from the query.
## Full Join:

Write a query using Full Join to get a comprehensive list of both gift recipients and gifts. Include recipients without gifts and gifts without assigned recipients.
Discuss the outcomes of the query and when such results might be useful in a Christmas context.

## gift_recipients table entries:
+--------------+---------------+
| recipient_id | recipient_name|
+--------------+---------------+
|      1       |    John       |
|      2       |    Mary       |
|      3       |    Sarah      |
|      4       |    Tom        |
|      5       |    Emily      |
+--------------+---------------+

## gifts table entries:
+---------+-----------+----------------+
| gift_id | gift_name | recipient_id   |
+---------+-----------+----------------+
|    1    |   Toy A   |       1        |
|    2    |   Book B  |       2        |
|    3    |   Candy C |       1        |
|    4    |   Toy D   |       3        |
|    5    |   Book E  |       6        |
+---------+-----------+----------------+

