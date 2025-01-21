# Customised DBMS (Database Management System)  

## Project Description  
The **Customised DBMS** is a Java-based console application that simulates basic database operations for managing employee records. This project demonstrates core database concepts, object-oriented programming principles, and user interaction through a menu-driven interface.  

## Features  
- **Employee Management**:  
  - Insert new employee records.  
  - Display all employee records or filter by specific ID or name.  
  - Update employee addresses by ID.  
  - Delete employee records by ID or name.  

- **Aggregate Operations**:  
  - Count the total number of employee records.  
  - Calculate the sum, average, maximum, and minimum salaries.  

- **Interactive Menu**:  
  - User-friendly interface to select and execute operations dynamically.  

- **Resource Management**:  
  - Supports database deletion and reinitialization during runtime.  

## Technologies Used  
- **Programming Language**: Java  
- **Data Structures**: LinkedList for storing employee records  

## How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/amanshaikh30/customised-dbms.git
   cd customised-dbms
   ```  
2. Compile the program using `javac`:  
   ```bash
   javac DBMS.java
   ```  
3. Run the program using `java`:  
   ```bash
   java DBMS
   ```  

## Usage  
Upon running the program, a menu will appear with the following options:  
1. Insert new record in the table  
2. Display all records from the table  
3. Display specific record by ID  
4. Display specific record by name  
5. Delete a record by name  
6. Count the number of records  
7. Calculate the total salary  
8. Calculate the average salary  
9. Find the maximum salary  
10. Find the minimum salary  
11. Update an employee's address  
12. Delete the entire database  
13. Exit  

Simply enter the corresponding option number to execute an operation.  

## Example Commands  
- **Insert a new record**:  
  Enter employee details (name, age, address, salary) to add a new record.  

- **Delete the database**:  
  Choose option 12 to delete the database. The program will automatically reinitialize a new database for further use.  

## Contributing  
Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements or new features.  

