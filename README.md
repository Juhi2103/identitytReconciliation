# Identity Reconciliation

Spring Boot web service to identify the identity of customers.


🔹 API Endpoints

POST /api/identify

#### Description: Identifies a customer and links related contacts.

## 🔹 Technologies Used

* Java 17

* Spring Boot

* PostgreSQL

## Structure:

identity-reconciliation/ <br>
│── src/ <br>
│   ├── main/ <br>
│   │   ├── java/com/bitespeed/IR/ <br>
│   │   │   ├── controller/ <br>
│   │   │   │   ├── ContactController.java <br>
│   │   │   ├── service/<br>
│   │   │   │   ├── ContactService.java<br>
│   │   │   ├── repository/ <br>
│   │   │   │   ├── ContactRepository.java <br>
│   │   │   ├── model/ <br>
│   │   │   │   ├── Contact.java <br>
│   │   │   ├── IdentityReconciliationApplication.java <br>
│   │   ├── resources/ <br>
│   │   │   ├── application.properties <br>
│   ├── test/ <br>
│   │   ├── java/com/bitespeed/IR/ <br>
│   │   │   ├── ContactServiceTest.java <br>
│── .gitignore <br>
│── README.md <br>
│── mvnw <br>
│── mvnw.cmd <br>
│── pom.xml <br>


## To How to Run Locally

* Clone the repository:

* Update application.properties with local PostgreSQL credentials.

* Run the application:


* Test via Postman at:


🔹 Author

👤 Juhi Namdev
