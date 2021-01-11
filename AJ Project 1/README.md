# PROJECT NAME

## Project Description

TRMS, or Tuition Reimbursement Management System is a full-stack web application that allows employees to submit requests for reimbursements for courses, events, and certifications. These requests can then be approved or rejected by the employee's direct supervisor, department head, and a benefits coordinator while the employee is able to track the status of their requests.

## Technologies Used

### Backend
* Java8
* Javalin
* PostgreSQL
* JDBC
* Hibernate
* DBeaver
* Maven

### Frontend
* HTML
* JavaScript
* CSS

### Testing
* JUnit


## Features

List of features ready and TODOs for future development
* User can log in
* User can submit requests for tuition reimbursement
* Managers and Department heads can skip certain approval steps
* Users can add comments and attachments to the requests
* Managers, Department Heads, and HR can request more information from previous approvers and the requestor
* HR can override the calculated amount to be reimbursed
* Limit unless overridden is $1000 per person per year
* Amount per event type is automatically caluclated

To-do list:
* Improve the layout
* Amount changer is buggy in Chrome but works in Firefox and needs to be fixed

## Getting Started
### git
git clone https://github.com/AJDoesntCode/TRMS

### Running the project
1. Using Eclipse or other IDEs that support Java 8
2. Open and run trmsJavalin.java file located in com.trms.app package.
## Usage
* Access the front-end of the web application by opening localhost:8080/html
