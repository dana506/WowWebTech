#### WowWebTech TEAM

# **Web Application for Fighting Food Waste: _Food Gone Good_**


### *_Scope_*

Developing a web application which allows the user to better manage their accounts and keep track of their finances.


### *_Description_*

This Web Application facilitates actions such as: synchronizing accounts, establishing monthly budgeting, tracking expenses and earnings and schedule bill payments.
The platform is based on a Single Page Application architecture. It is a responsive application being accessible on a desktop, mobile or tablet browser (depending on user preferences).


### *_(Minimal) Functionality_*

As a user, I can connect multiple bank accounts from as many financial institutions as I desire using their external API.

As a user, I can track everything which counts as an expense or income stream, based on a specific spending category, predict my monthly budget and log my recurring bills.

As a user I can choose to see the charts and reports (PDF, CSV) of my expenses based on categories. Nevertheless the application has an additional feature that allows me, the user, to forecast my spending behaviour.

As a user, I can set budget alerts and manage my savings in a recurring manner.


### *_Examples_*

Mint
https://www.mint.com

Monzo
https://www.monzo.com


### *_Team Management KANBAN Board on Trello Website_*

https://trello.com/b/i0uR1nT8/wowwebtech-project-kanban



### *_API REST_*

+ _Requests_

```
GET / CATEGORIES / :ID / INCOME 

GET / CATEGORIES / :ID / EXPENSES

GET / expenses?search={category}&orderBy={orderBySum}

GET / expenses?search={category}&orderBy={orderByDate}

GET / income?search={category}&orderBy={orderBySum}

GET / income?search={category}&orderBy={orderByDate}

PUT / SAVING

GET / saving?search={sum}&orderBy={orderByDate}

GET/ SAVING_TOTAL

PUT / RECURRING_BILL

DELETE / RECURRING_BILL

POST / CHART

POST / FORECAST

POST / PDF

PUT / BUDGET_ALERTS

POST / SYNC ACCOUNTS
```

+ _Responses_

```
 HTTP/1.1
 
 HTTP/1.1 404 Not Found
 
 HTTP/1.1 200 OK. The request has succeeded.
 
 HTTP/1.1 [ 
  {
    "Expense Category": "Utilities",
    "Expense Sum ": "200.00",  
    "Expense Date": "20.05.2020"
  } ]
  
  HTTP/1.1 [ 
  {
    "Total Savings ": "4500.00",  
  }]
  ```


### *_Mockups for Application Interface with Components & Entities, API Calls and User Actions_*


![Step 1](https://github.com/dana506/WowWebTech/blob/main/Pictures/1.png)

![Step 2](https://github.com/dana506/WowWebTech/blob/main/Pictures/2.png)

![Step 3](https://github.com/dana506/WowWebTech/blob/main/Pictures/3.png)

![Step 4](https://github.com/dana506/WowWebTech/blob/main/Pictures/4.png)

![Step 5](https://github.com/dana506/WowWebTech/blob/main/Pictures/5.png)
