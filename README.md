#### Documentation Part-A

#### R1. Description of your website, including:

##### Purpose
To provide a tool for the recording of personal expense data. Gives users to collate expenses by category and provide visual representation of spending habits.

##### Functionality / Features
User registration, sign-in and authentication. Creation of expense instances, including
Description, Category, Date and Value (AUD). Ability to edit existing expense instances, or delete entries. 
Filtering of existing expenses by date. Visual representation of expense trends (charting).

##### Target Audience
Users with the ability to interact with a simple interface, either desktop or mobile based. Those who want an online resource for recording and displaying spending history. 

##### Tech Stack
1. MERN Stack:
* Front End (Client):
   * React
   * HTML
   * CSS
* Back End (Server):
   * Express 
   * Node
* Database:
   * Mongo DB

2. JavaScript
###### Other Tools Used:
* Lucidchart - To Draw Data Flow Diagram.
* Draw - To draw Architectural Application Diagram.
* Balsamiq.cloud - For drawing Wireframes.
* Cardboardit - For Creating User Stories.
* Trello - For Project Management.
---
#### R2. Dataflow Diagram

DFD for users: 
![Dfd-Of-Users](docs/Dfd/dfd1.png)

DFD for transactions:

![Dfd-of-transactions](docs/Dfd/dfd2.png)

**External Entities:**
* User

**Processes:**
* 1.0: Regiser a new user and store the user details in database
* 2.0: Login user with credential.User will be authenticated and get appropriate response.
* 3.0: Update user information according to the request from user. It will also update the database.
* 4.0: Delete user and update the database by removing corresponding user details.
* 5.0: Add expenses, create new expense details for the authorised user. And stores details to the transactions database.
* 6.0: View all expense details.
* 7.0: View a single expense.
* 8.0: Update expense details based on the request from user.Also update the databse.
* 9.0: Delete expense based on the request from user. also update the database.
* 10.0: Search expense details based on the request from user.
* 11.0: Shows reports of expense based on the request from user.

**Data Storages:**

* users: It stores all details of a user.
* transactions: it stores all the transaction details of a user
---
#### R3. Application Architecture Diagram

![Application-architecture-diagram](docs/architectural-diagram/final-arch-diagram.png)

---
#### R4. User Stories:

Initial user stories:
![userstory1](docs/userstories/user1-9-7-20.png)


Final user stories:
![userstory2](docs/userstories/User-story2.png)

Link to the user-story: https://app.cardboardit.com/maps/guests/d2f893bfc5b428b4efd0ad359293b037ec8cb0df16c620770199e49a03f2bd4b

---
#### R5. Wireframes for multiple standard screen sizes, created using industry standard software
Mobile <br>

![wireframe-login-reg-landing](docs/wireframes/m-login-reg-landing.png)

![wireframe-add-list-edit](docs/wireframes/m-add-list-edit.png)

<img src="docs/wireframes/m-reports.png" alt="wireframe-reports" height="310"/>


Desktop<br>

![wireframe-login](docs/wireframes/d-login.png)

![wireframe-register](docs/wireframes/d-register.png)

![wireframe-landing-page](docs/wireframes/d-landing-page.png)

![wireframe-add-expense](docs/wireframes/d-add-expense.png)

![wireframe-expense-list](docs/wireframes/d-expense-list.png)

![wireframe-edit-expense](docs/wireframes/d-edit-expense.png)

![wireframe-reports](docs/wireframes/d-reports.png)

----

#### R6. Screenshots of your Trello board demonstrating use throughout the initial stages of the project
04/07/2020
![screenshot200704](docs/Trello/trello-screenshot-200704.jpg)

08/07/2020
![screenshot200708](docs/Trello/trello-screenshot-200708.png)

09/07/2020
![screenshot200709a](docs/Trello/trello-screenshot-200709a.png)

![screenshot200709b](docs/Trello/trello-screenshot-200709b.png)

10/07/2020
![screenshot200710a](docs/Trello/trello-screenshot-200710a.jpg)

![screenshot200710b](docs/Trello/trello-screenshot-200710b.jpg)

![screenshot200710c](docs/Trello/trello-screenshot-200710c.jpg)

![screenshot200710d](docs/Trello/trello-screenshot-200710d.jpg)

![screenshot200710e](docs/Trello/trello-screenshot-200710e.jpg)
