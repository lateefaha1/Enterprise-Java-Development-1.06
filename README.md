# Enterprise-Java-Development-1.06

## Employee and Intern Classes
1. Create an Employee class to represent an employee of a company. The class should have name, email, age, salary properties and appropriate getters and setters.
2. Create an Intern class that extends from Employee. The Intern class should have a salary limit of 20000 (constant).
3. Implement validation in the Intern class to ensure that an intern is not created (or salary updated) with a salary that exceeds the maximum allowed value.
4. Write a program that creates 10 Employee objects and prints all of their properties (name, email, age, salary) to a file named employees.txt.

## Tips
- Be sure to consider the relationship between the Employee and Intern classes when designing your solution.
- Think about the different properties and behaviors that are applicable to both Employee and Intern objects and consider how you can use inheritance to avoid duplication of code.
- Use appropriate access modifiers (e.g. private, protected, public) to control the visibility of your class properties and methods.
- Make sure to handle edge cases and handle them appropriately (e.g. what happens if an Intern object is created with a salary that exceeds the maximum allowed value?)
