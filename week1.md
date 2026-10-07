
# 📚 Week 1 — Full Stack Development

This week we learned the basics of Full Stack Development, how a food ordering application works internally, and the fundamentals of Git and GitHub.

##  How Food Ordering Works Internally

When a user orders food through an application like Zomato, multiple components work together to process the order.

###  Basic Flow


User
  ↓
Frontend
  ↓
API Request
  ↓
Backend Server
  ↓
Database
  ↓
Restaurant
  ↓
Delivery Partner
  ↓
User


###  Technical Flow

1. User selects food items and places an order.
2. Frontend sends an HTTP request to the backend API.
3. Backend receives and validates the request.
4. Backend processes the order and communicates with the database.
5. Order details are stored in the database.
6. Restaurant receives the order.
7. Restaurant accepts and prepares the order.
8. Delivery partner is assigned.
9. Backend updates the order status.
10. Frontend displays the updated order status to the user.

###  Example API Flow

text
Frontend
   ↓
POST /api/orders
   ↓
Backend Server
   ↓
Database
   ↓
Order Created
   ↓
Response
   ↓
Frontend


## Git Basics

Git is a version control system used to track changes in code and manage different versions of a project.

GitHub is a platform used to host Git repositories online and collaborate with other developers.

##  Git Commands

### Initialize a Repository


git init


### Check Repository Status


git status


### Add Files to Staging


git add .


### Commit Changes


git commit -m "Initial commit"


### Connect Local Repository to GitHub


git remote add origin <repository-url>


### Check Remote Repository


git remote -v


### Push Changes to GitHub


git push -u origin main


### Pull Changes from GitHub


git pull


### Clone a Repository


git clone <repository-url>


### View Commit History

git log


### Create a New Branch


git branch <branch-name>


### Switch to a Branch


git checkout <branch-name>


### Create and Switch to a New Branch


git checkout -b <branch-name>


 Basic Git Workflow


git status
git add .
git commit -m "Update Week 1"
git push




Cherry-pick is used to apply a specific commit from one branch to another branch.


git cherry-pick <commit-hash>


Key Takeaways

* Learned how a food ordering application works internally.
* Understood how frontend, backend, APIs, and databases interact.
* Learned the basics of Git and GitHub.
* Learned how to initialize and manage a Git repository.
* Learned how to stage, commit, and push changes.
* Learned the basic Git workflow.



 In VS Code

Your folder can look like this:


learning-repository/
│
├── week1.md
│
└── README.md

Then in the VS Code terminal:


git add week1.md
git commit -m "feat: added week 1 learning notes"
git push



