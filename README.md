**ATM INTERFACE**:-

The ATM interface developed using Java, MySQL, and JDBC is a comprehensive solution that allows users to perform various banking tasks efficiently. 
The interface provides the following key features:

***Transaction History***: Users can view their transaction history, which includes details such as transaction type (deposit or withdrawal), amount, current balance, and timestamp.The transaction history is stored in a MySQL database and can be retrieved and displayed in the interface.

***Deposit***: Users can deposit money into their account through the ATM interface.
         The interface allows them to enter the amount to be deposited, and the balance is updated accordingly in the database.
         
***Withdraw***: Users can withdraw money from their account using the ATM interface. 
          They can specify the withdrawal amount, and if the balance is sufficient, the transaction is processed and reflected in the database.
          
***Check Balance***: Users can check their account balance through the ATM interface. 
               The current balance is fetched from the database and displayed to the user.
               
The ATM interface utilizes Java for the application logic, MySQL as the database management system, and JDBC (Java Database Connectivity) for establishing a connection between the Java application and the MySQL database. JDBC allows executing SQL queries and statements to interact with the database seamlessly.

The application maintains a secure connection with the database, ensuring data privacy and integrity. It provides a user-friendly interface for customers to perform banking transactions conveniently.
