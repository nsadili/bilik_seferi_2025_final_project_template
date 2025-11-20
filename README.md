# Final exam - Bilik Səfəri (Gəncə)

## **Project Ideas (Choose One)**

Students must select **one project idea** and implement it individually.

- **Digital Banking Simulation**
  - Add, update, delete, and list **customer profiles**.
  - Create, update, delete, and view **bank accounts** for each customer.
  - Perform **deposit**, **withdrawal**, and **money transfer** operations.
  - Record and list **transactions** for every account.
- **Student Management System**
  - Add new students; update, delete, and list existing students.
  - Add and list **courses**.
  - Enroll a student into a course; list all courses a student is enrolled in.
  - View all students enrolled in a particular course.
- **Simple Task Manager**
  - Add a new task with title, description, due date, and assigned person.
  - Update, delete, and list tasks.
  - Move tasks between statuses (e.g., "To Do", "In Progress", "Done").
  - List tasks approaching or past their deadlines and notify the assigned person.
  - View all tasks assigned to a specific person.
- **Basic E-Commerce Simulation**
  - Add, update, delete, and list **products**.
  - Create and manage **customer profiles**.
  - Allow customers to **place an order** for one or more products.
  - Reduce product stock after an order is placed.
  - Show error messages for invalid actions (e.g., "out of stock").

## **Guidelines**

- **Language & Tools**: Java 17+, Spring Boot (for web projects), Git for version control, MySQL/PostgreSQL for database.
- **Scope**: Keep it simple. Focus on **working features**, not advanced optimizations.
- **Documentation**:
  - Write a short README (project description, how to run).
  - Comment code to explain logic. (Do not overuse comments, simple Javadoc and super-necessary ones)
- **Version Control**:
  - Push code to GitHub (minimum 2 commits per week showing the progress).
- **Deadline**: Submit within **30 days** of assignment.
- **Mentor Support**: Students may ask mentors for clarification but must write code themselves.

## **Rules**

- **Individual Work**: Collaboration is allowed for discussion, but code must be original.
- **Minimum Requirements**:
  - Use of Streams/Lambdas.
  - REST API implementation with Spring Boot.
  - Proper validation (e.g., empty fields, invalid IDs).
  - At least **3 classes** with proper OOP design.
  - Use of **Collections** (ArrayList, HashMap, or Set).
  - At least **1 exception handling scenario**.
  - For database projects: minimum **2 tables** with a relationship (e.g., Student-Course).
  - Create a **Swagger specification file** for your REST API.
  - Use at least **one join query** (SQL or JPQL).
  - Deploy **PostgreSQL in Docker** and connect your project to it.
  - -ADD Liquibase
- **Bonus Points**:
  - Use **RabbitMQ** as a message broker:
    - One service acts as **producer**.
    - Another service acts as **consumer**.
  - Implement **Caching**:
    - Either **in‑memory caching** (e.g., @Cacheable)
    - Or **Redis caching** via Spring Boot integration.

# **Final Exam Project Milestone Plan (4 Weeks)**

## **Week 1 - Foundation Setup**

**Goal:** Get started with the project skeleton and basic features.

- Choose **one project idea** (Student Management, Library Tracker, Task Manager, or E-Commerce).
- Create a **GitHub repository** and push an initial commit.
- Define **main classes** (e.g., Student, Book, Task, Product).
- Implement **basic CRUD operations** (Add, List, Delete).
- Write simple console outputs or REST endpoints (if using Spring Boot).
- Document progress in README (project description + setup instructions).

## **Week 2 - OOP & Error Handling**

**Goal:** Apply OOP principles and handle invalid inputs.

- Add **inheritance/relationships** (e.g., Student-Course, Product-Order).
- Use **Collections** (ArrayList, HashMap) to store data temporarily.
- Implement **exception handling** (e.g., invalid ID, empty input).
- Add **basic validation** (e.g., name cannot be empty).
- Make at least **2 Git commits** showing progress.

## **Week 3 - Persistence & APIs**

**Goal:** Connect project to a database and expose functionality.

- Set up **MySQL/PostgreSQL database** with minimum 2 tables.
- Use **Spring Data JPA** for persistence (if applicable).
- Implement **REST endpoints** (for Library Tracker / E-Commerce).
- Add **Streams/Lambdas** for filtering/searching data.
- Update README with database setup instructions.

## **Week 4 - Finalization & Submission**

**Goal:** Polish, document, and prepare for evaluation.

- Add **final features** (e.g., borrowing books, placing orders, marking tasks complete).
- Ensure **exception handling + validation** are consistent.
- Write **README** with:
  - Project overview
  - How to run (steps)
  - Example inputs/outputs
- Push final commits to GitHub.
- Prepare a **short demo (5-10 min)** to present project flow.

# **Rules for Milestone Completion**

- **Weekly commits** required (minimum 2 per week).
- **Code must compile and run** at each milestone.
- **README must be updated weekly** with progress notes.
- **Update the CHECKLIST.md** for each commit.
- **No copy-paste from peers** - originality is mandatory.
- **Ask mentors only for clarification**, not for code writing.

# **Final Project Checklist**

## Week 1 - Setup & Basics

- \[ \] Pick one project idea (Student System / Library / Task Manager / E‑Commerce)
- \[ \] Create GitHub repo & first commit
- \[ \] Define main classes (e.g., Student, Book, Task, Product)
- \[ \] Implement Add / List / Delete functions
- \[ \] Update README with project description

## Week 2 - OOP & Error Handling

- \[ \] Add inheritance or relationships (e.g., Student-Course, Product-Order)
- \[ \] Use Collections (ArrayList, HashMap, Set)
- \[ \] Handle exceptions (invalid ID, empty input)
- \[ \] Add basic validation (e.g., name not empty)
- \[ \] Update README with database setup instructions

## Week 3 - Database & APIs

- \[ \] Create database (minimum 2 tables with relationship)
- \[ \] Deploy **PostgreSQL in Docker** and connect project to it
- \[ \] Connect with Spring Data JPA (if using Spring Boot)
- \[ \] Implement REST endpoints (for Library / E‑Commerce projects)
- \[ \] Use Streams/Lambdas for filtering/searching
- \[ \] Use at least **one join query** (SQL or JPQL)
- \[ \] Update README with database setup instructions

## Week 4 - Final Polish & Submission

- \[ \] Add final features (borrow books, place orders, mark tasks complete)
- \[ \] Ensure exception handling + validation everywhere
- \[ \] Create a **Swagger specification file** for your REST API
- \[ \] Write README with: overview, run steps, example inputs/outputs
- \[ \] Push final commits to GitHub

## Bonus Objectives (Optional, Extra Credit)

- \[ \] Use **RabbitMQ** as a message broker (one service producer, another consumer)
- \[ \] Implement **Caching** (either in‑memory or Redis)
