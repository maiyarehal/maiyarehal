Hi! I'm Maiya Rehal, an undergraduate at ECU majoring in computer science with a passion for data science. 
I love working on projects that can be applied to real world settings and improve the daily lives of others.
When I'm not coding, I enjoy reading, going to the beach and hanging out on the boat.

Skills -
Languages: Python, Java, C, C++
Web Development: HTML, CSS (introductory), JavaScript (introductory)
Tools: Visual Studio Code, Eclipse, Visual Studio
Databases: MySQL (introductory), PowerBi (introductory)
Other: UI/UX design

Projects -
HR Simulation Project
A system for managing a payroll application using a generic dataset (DataSetGeneric) and a variety of classes and interfaces for handling different types of employees (Employee, Manager, Executive). 
The application provides functionality for adding employees, managers, and executives, listing them, sorting them, and displaying the highest-paid employee.

High-level overview of the code:

DataSetGeneric<T extends Measurable>: A generic dataset class that holds a list of items that implement the Measurable interface.
Provides methods to add items, get the size of the dataset, and retrieve a list of items. It also supports retrieving a filtered list based on a Screener.
Measurable: An interface with a method getMeasure() which returns an integer measure.
Payroll: The main class for the payroll application, providing a menu for user interactions and methods for handling various actions like adding employees, listing employees, sorting, and displaying payroll information.
Employee: A class representing a generic employee with a name and salary. Implements the Measurable interface by providing the getMeasure() method, which returns the salary as an integer.
Manager: A subclass of Employee that includes an additional attribute for the department. Overrides the toString() method to include the department in the string representation.
Executive: A subclass of Manager that includes an additional attribute for the bonus. Overrides the getSalary() method to include the bonus in the total salary. Overrides the toString() method to include the bonus in the string representation.
Screeners: EmployeeOnlyScreen, ManagerOnlyScreen, ExecutiveScreen: Implementations of the Screener interface to filter employees based on their type.
Unit Tests: EmployeeTest, ManagerTest, ExecutiveTest, DataSetGenericsTest: Unit tests for the various classes to ensure they behave as expected.
Utils: A utility class providing static methods for displaying menus and lists to the user and handling user input.

Key Methods in Payroll - 
Adding Employees: Methods like addEmployee, addManager, and addExecutive prompt the user for input and create new instances of the respective classes, adding them to the dataset.
Listing Employees: Methods like displayEverybody, displayOnlyEmployees, displayOnlyManagers, and displayOnlyExecutives retrieve and display lists of employees based on the filters applied by the screeners.
Sorting Employees: Methods like displaySortedByName and displaySortedBySalary sort the employees based on the specified criteria before displaying them.
Payroll Generation: generatePayroll calculates and displays the total payroll by summing the salaries of all employees.

Example Usage - 
The main method initializes a DataSetGeneric<Employee> and enters a loop where it repeatedly presents the user with a menu of options. 
Depending on the user's choice, it calls the corresponding method to perform actions like adding employees, listing them, or sorting them.


Education - 
Undergraduate in Computer Science
East Carolina University - 08/2022 - 05/2025 (expected)

Contact
Feel free to reach out to me via LinkedIn or email.
