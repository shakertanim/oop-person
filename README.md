Instructions:

Part 1: Creating Your First OOP Class (7.5 points)

Create a Java class named "Person" with the following attributes:
name (a String)
age (an int)
email (a String)
Implement a constructor in the "Person" class to initialize these attributes.
Add a method named displayInfo() in the "Person" class that displays the person's name, age, and email.
Part 2: Creating a Driver Class and Instantiating Objects (7.5 points)

Develop a separate Java class called "PersonDemo."
In the "PersonDemo" class, create two instances of the "Person" class and set their attributes with sample data.
Call the displayInfo() method for both instances to display their information.
Part 3: Local Variables and Return Statement (7.5 points)

In the "displayInfo()" method of the "Person" class, declare a local variable named address (a String).
Try to access this local variable from the "PersonDemo" class and explain the result. Provide the reason why this happens.
Modify the "Person" class by adding a new method called calculateBirthYear(int currentYear). This method should take the current year as an argument and return the birth year of the person based on their age.
In the "PersonDemo" class, call the calculateBirthYear(int currentYear) method for one of the persons and display their birth year.
Part 4: Specialized Methods (7.5 points)

Extend the "Person" class by implementing a method named isAdult(). This method should check whether the person is an adult (age >= 18) and return a boolean value accordingly.
In the "PersonDemo" class, call the isAdult() method for both persons and display whether they are adults or not.
Sample Output:

Here's the expected sample output for the "PersonDemo" class:

Person 1:
Name: John
Age: 25
Email: john@example.com
Person 2:
Name: Alice
Age: 17
Email: alice@example.com
Person 1's Birth Year: 1997
Person 2's Birth Year: 2006
Person 1 is an adult: true
Person 2 is an adult: false
