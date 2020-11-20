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



### *_Mockups for Application Interface with Components & Entities, API Calls and User Actions_*


![Step 1](https://github.com/dana506/WowWebTech/blob/main/frontend/Documentation/Pictures/1.png)

![Step 2](https://github.com/dana506/WowWebTech/blob/main/frontend/Documentation/Pictures/2.png)

![Step 3](https://github.com/dana506/WowWebTech/blob/main/frontend/Documentation/Pictures/5.png)

![Step 4](https://github.com/dana506/WowWebTech/blob/main/frontend/Documentation/Pictures/4.png)

![Step 5](https://github.com/dana506/WowWebTech/blob/main/frontend/Documentation/Pictures/3.png)



### *_API REST_*

+ _Requests_

```
GET / Categories/ :ID / Inventory

GET / Categories/ :ID/ Create Friend Group

GET / inventory?search={products/ :available}&orderBy={orderByClaimedBy}

GET / inventory?search={products}&orderBy={orderByDateExp}

GET / Products From DB?search={Products/ :count}&orderBy = {Category}

PUT / Send Invite/ Friend Group Name/ Products 

PUT / FG Name/ Add New Friend Group

PUT / FG Name/ Send Invite Friend Group

PUT / Alert/ Inventory

DELETE / Friend Group Name / :ID/ Create Friend Group

DELETE / Product/ :ID/ Inventory

POST / Claim Now/ Products From DB

POST / Alerts Settings/ Inventory

POST / Facebook/ :Product/ Inventory
```

+ _Responses_

```
 HTTP/1.1
 
 HTTP/1.1 404 Not Found
 
 HTTP/1.1 200 OK. The request has succeeded.
 
 HTTP/1.1 [ 
  {
    "Inventory Product": "Tofu",
    "Inventory Category": "Dietary Preferences" "Vegan",
    "Inventory Date Exp": "20.05.2020", 
    "Inventory Available": "NO", 
    "Inventory Claimed by": "Alex Rosenberg"
    } ]
  
  HTTP/1.1 [ 
  {
    "Friend Group Name": "The Plant based ones",
    "Friends Group Category": "Dietary Preferences",
    "Friends Group Subcategory": "Vegan",   
    }]
  ```

### *_Team Management KANBAN Board on Trello Website_*

https://trello.com/b/i0uR1nT8/wowwebtech-project-kanban


### *_Team Roles_* 


#### PRODUCT OWNER:
_Dana Buzatu (Data Analyst)_

#### PROCESS COORDINATOR: 
_Ana Cojocaru (Researcher)_

#### FULL-STACK DEVELOPERS:
_Alexandra Becheru, Rafael Belcu, Dana Buzatu, Ana Cojocaru_

#### TESTERS:
_Alexandra Becheru (PR), Rafael Belcu (Proof Reader)_

