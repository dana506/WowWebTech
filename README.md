#### WowWebTech TEAM

# **Web Application for Fighting Food Waste:**
# **_Food Gone Good_**


### *_Scope_*

Developing a Web Application which allows the user to better manage their groceries by sharing the food they no longer need with friends and accountancies.


### *_Description_*

*_Food Gone Good_* Web App encourages a sense of community, frugality and intentional living with regards to our grocery choices. These are achieved in a fun way by allowing the user to log their groceries that are no longer needed, provide an expiration date and categorize in order to suit other members of the community's tastes. For example, some of the categories could include: dietary choices, allergies, food preferences or even food groups. Considering these categories, the user can also include their friends and accountancies' preferences and group them in order for them to be notified to check the products up. Any user can claim products in other user's list. The app allows sharing on social media platforms.


### *_Examples_*

Olio

https://olioex.com/

Food Cowboy

https://www.foodcowboy.com

Food Rescue Hero

https://412foodrescue.org/programs/foodrescuehero/

Food Tank

https://foodtank.com/

### *_Team Management KANBAN Board on Trello Website_*

https://trello.com/b/i0uR1nT8/wowwebtech-project-kanban


### *_Team Roles_* 


#### PRODUCT OWNER:
_Dana Buzatu (Researcher)_

#### PROCESS COORDINATOR: 
_Ana Cojocaru (Data Analyst)_

#### FULL-STACK DEVELOPERS:
_Alexandra Becheru, Rafael Belcu, Dana Buzatu, Ana Cojocaru_

#### TESTERS:
_Alexandra Becheru (PR), Rafael Belcu (Proof Reader)_


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


![Step 1]

![Step 2]

![Step 3]

![Step 4]

![Step 5]


