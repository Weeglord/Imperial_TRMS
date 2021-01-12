# Imperial TRMS

## Project Description

The Imperial Senate has decided to charter the creation of a Tuition Reimbursement Management system available to all Imperial Officers and StormTroopers.
Users can create new requests and provide appropriate information before submitting the request to their supervisor, the form must then be approved by the
department head, and the benefits coordinator. Users will have to pass an approprate test or provide a presentation before the funds can be disbursed.

## Technologies Used

* PosgreSQL
* Hibernate, JDBC
* Angular
* JUnit

## Features


* Login
* Create new Reimbursement Form
* Event must be more than 1 week away to submit form
* If event is less than 2 weeks away the request is marked as urgent
* View submitted forms status
* Supervisor/DepartmentHead/BenCo approval required in order
* If approval not given in 2 weeks request is auto approved except for BenCo approval
* Supervisors and above can request information from those lower in the chain
* If an information request has been made it will appear in the notifications tab for both parties
* Files can be uploaded when creating a request, and when submitting grade results
* BenCo must approve of a grade submission before disbursement
* Only the owner and the appropriate superior for a given stage can view the request
* Requests can be rejected by superiors if they have access to the request
* Users may submit an email of approval by an appropriate supervisor as a file upload to "fast-track" their request to the appropriate step

To-do list:
* Add system to register accounts
* Add BenCo approval to "fast-track" email uploads
* Add more imperial propaganda

## Getting Started
   
git clone https://github.com/Weeglord/Imperial_TRMS.git

#Backend:
Use Maven update to build the project, run TRMSJavalin.java

#Frontend:
Navigate to http://localhost:8080 on web browser

## Usage

# Employees
* Login (please contact your local imperial office if you do not have an account)
* Address open information requests in the notifications tab
* Create a new Tuition Reimbursement Form
* Fill out all necessary information and hit submit

# Superiors
* Login (please contact your local imperial office if you do not have an account)
* Address open information requests in the notifications tab
* Expand and view a desired form
* Accept, Reject, or request information as desired

## License
<MIT License>
