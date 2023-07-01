
# Context
At Etaily, we understand that data is key to leveraging new opportunities. We need to be able to consume, explore and understand a wide range of data. We have chosen a development approach to Data Engineering in contrast to traditional drag-and-drop BI tools. Modern programming languages and libraries allow us to develop scalable data pipelines that are powerful and easier to test and observe. 

---
## Time Limit: 48 hours upon receipt of the exercise
---
## Instructions

1. Your output will be a **link to your repository** containing your answers on each of the task stored in your personal version control account that the team will clone for checking. You can create a separate folder that would contain scripts, explanations, documentations, etc. related to your solution.
2. You can use Google etc. to search for help for the tasks. We want to replicate a normal working environment. 
3. We want to see your skills as a developer, so write proper code but also keep the time limit in mind. 
4. If you have problems with one task, skip it and continue with the next one. Donâ€™t spend all your time on it. 
5. If you have any questions, do not hesitate to ask!

---

## Task # 1 SQL Queries

**Customer Table: "customer"**

| id | first_name | last_name  | gender | date_of_birth | country |
|----|------------|------------|--------|---------------|---------|
| 1  | Jason      | Smith      | male   | 1982-05-28    | USA     |
| 2  | Max        | Mustermann | male   | 1980-07-18    | Germany |
| 3  | Will       | Myer       | male   | 1981-03-30    | England |
| 4  | Christin   | Dawn       | female | 1978-08-02    | USA     |
| 5  | Angela     | Gutierez   | female | 1986-01-16    | Spain   |
| 6  | Peter      | Jackson    | male   | 1958-12-05    | USA     |

**Order Table: "order"**

| id | order_nr   | sum    | fk_customer |
|----|------------|--------|-------------|
| 1  | 2783292423 | 100.85 | 2           |
| 2  | 4784232411 | 77.34  | 3           |
| 3  | 3783292423 | 30.99  | 5           |
| 4  | 9368315313 | 33.55  | 2           |


**Order Item Table: "order_item"**

| id | sku     | fk_order |
|----|---------|----------|
| 1  | ABCDEF  | 1        |
| 2  | ABCDEF  | 1        |
| 3  | OHSDLF  | 1        |
| 4  | 1737234 | 2        |
| 5  | KLSHA   | 3        |
| 6  | OHSDLF  | 3        |
| 7  | GHJSK   | 4        |


Given the tables above.

1. Write a query which select all female customers

2. Write a query which prints out all customer names with the number of orders they did

3. Write a query which prints out customers with the money they spend excluding customers without any orders

4. Write a query which prints out the order nr of all orders with at least 2 items

---

## Task # 2 Python Code
Create a Python script that fetches tweets with hashtag **#ecommerce** from the previous day.

Sample scenario: August 1 2022 extraction will fetch the data from July 31 2022). The file should be a list of json objects.

(**Optional**: If you can include a feature to store the output file into a cloud storage, please do so.)

---
## Task # 3 Table Design
From the data that you got from task#2, imagine reading millions or billions of rows from it. Describe a way on how you will design the table so that processing or querying the table will be optimized.

---

## Task # 4 Data Pipeline Design in Cloud Setup
Assuming you want to deploy an automated solution for task#2 in a cloud setup to be available to an end user via a BI platform. Give a short high level description of a possible approach and some considerations that would affect your choices.

---

## Optional: Please rate this test, if youâ€™d like to.

What do you think about this test? 

Did it have a good distribution of tasks from different areas? 

Did we miss something important? 

Did it have a reasonable difficulty for an online coding test?

Any other comments?


# Criteria for Success

We will check:

- How you package your app
- How you let other developers know what it does
- How you would present it to a non-technical audience
- How effective you were on your logic
- How you ensured quality
- How did you implement it - design patterns
- How reusable, complex and clean your code is

---

# What else are we looking for?
- Computer Science - Some algorithms can make a difference here...
- Principles - These are the things you kind of learn by doing (testing, monitoring, alerting, etc)
- Language - How much you know about programming languages
- Optimisations - Maybe you know interesting ways of optimising software?
- Frameworks - Ok, we know you can show-off all that you know but, engineers tend to master some cool frameworks!
---

We want you to succeed! If you got this assignment, it means that we are already, kind of, seeing a potention in you... 
 
In case you have more questions, please, get in touch with us so we can make this assignment every day a little bit better!
 
If you have any questions or ideas that you want to discuss, please contact us by email (francis.ambrocio@etaily.com.au; alexis.cuntapay@etaily.com.au). 

We hope that you enjoy this assignment and take the time to show us your skills. 