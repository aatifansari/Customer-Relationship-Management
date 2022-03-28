# Customer-Relationship-Management
Full-stack webapp to perform CRUD operation on database and uses JSP template engine.


![CRM-view](https://user-images.githubusercontent.com/44142827/160386635-16573dc9-016c-4e41-8f5e-fb1905041443.PNG)

Customer object fields

- id
- firstName
- lastName
- email

Endpoints Mapping

Base Context-Path

http://{host_name}/customer - /customer is the base context-path for CustomerController class.

http://{host_name}/customer/list - It map with listCustomers() method that retrieve all customers data from database.

### Add Customer Button -

Endpoint - http://{host_name}/customer/showFormForAdd
It map with showFormForAdd() method to open new Add Customer Form with First Name, Last Name and Email fields.




# Technology Stack

- Framework - Spring MVC
- View Technology - JSP( Java Server Pages)
- ORM - Hibernate
- RDBMS - MySQL
- Server - Tomcat
