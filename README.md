# bank_account_encapsulation.py
Learning and demonstrating Object-Oriented Programming (OOP) concepts, specifically:
1. Encapsulation - The fundamental principle of bundling data (attributes) and methods (functions) within a class, hiding internal details from outside access
2. Access Modifiers - Understanding how Python implements:
    2.1 Public (default) - no prefix, accessible everywhere
    2.2 Protected (single underscore _) - internal use by convention
    2.3 Private (double underscore __) - true data hiding via name mangling
3. BankAccount Example - A practical demonstration showing:
    3.1 Why we protect sensitive data like account balance
    3.2 How getter methods provide controlled read access
    3.3 Why operations like deposit/withdraw should go through methods, not direct attribute modification
4. Language Used:
    4.1 Python 3
    4.2 Uses OOP features: classes, methods, attributes, constructors

TOPIC: Encapsulation and Access Modifiers in Python
Concepts Covered:
1. Lists, Dictionaries, Functions (mentioned as prerequisites)
2. Encapsulation - Wrapping data and methods into a single unit
3. Access Modifiers - Controlling access to class attributes and methods

Encapsulation:
- Mechanism of wrapping attributes and code acting on methods together as a single unit
- Attributes of a class are hidden from other classes and can be accessed only 
  through methods of their current class
- Also known as 'data hiding'

Benefits of Encapsulation:
1. Simplifies complexity - hides internal implementation details
2. Protects data - prevents accidental or unauthorized modification

Python Convention for Access Control:
- Single Underscore Prefix ('_') : Indicates attribute/method should be treated 
  as 'private' or 'internal' (convention-based, not enforced)

Access Modifiers:
1. Public (+)
   - Accessible from anywhere (within class, subclasses, and outside)
   - Default in Python (no prefix)

2. Protected (#)
   - Intended for use within class and its subclasses
   - Can be accessed outside but by convention should not be
   - Denoted by single underscore prefix '_'

3. Private (_)
   - Meant to be accessed only within the class
   - NOT accessible from outside (name mangling applies)
   - Denoted by double underscore prefix '__'
   - Python implements this through name mangling

# library_catalog_system.py
Library Catalog System
Activity 230609 - Demonstrates OOP principles (encapsulation, classes, methods)

ACTIVITY ASSIGNMENT BELOW
230609 - Main Activity
Activity 1: Building a Library Catalog System
Objective: Implement a library catalog system using encapsulation principles.

Instructions:
Define a class called Book with the following attributes and methods:
Attributes:
- title : The title of the book.
- author: The author of the book.
- publication_year: The year the book was published.
- is_available: Indicates whether the book is available for borrowing.

Methods:
- __init__(self, title, author, publication_year): Initializes the book object with the given title, author, and publication year. Set is_available to True by default.
- get_title(self): Returns the title of the book.
- get_author(self): Returns the author of the book.
- get_publication_year(self): Returns the publication year of the book.
- is_book_available(self): Returns the availability status of the book.
- borrow_book(self): Marks the book as borrowed (sets is_available to False).
- return_book(self): Marks the book as returned (sets is_available to True).

Create a list called library to store the book objects.

Implement the following functionality in the main program:
  1. Prompt the user to enter book details (title, author, publication year).
  2. Create a Book object with the provided details and add it to the library list.
  3. Repeat the above step to add multiple books to the library.
  4. Display the available books in the library.
  5. Prompt the user to choose a book to borrow by entering its index.
     - If the chosen book is available, mark it as borrowed and display a success message. Otherwise, display an error message.
  6. Display the available books in the library again.
  7. Prompt the user to choose a book to return by entering its index.
     - If the chosen book is not available, mark it as returned and display a success message. Otherwise, display an error message.
  8. Display the available books in the library one final time.

Note: You can use the input() function to get user input and the print() function to display messages and book information.

Grading:
First 1-10 submission without errors --> 100 points
Second 11-20 submission without errors --> 90 points
Third 21-30 submission without errors --> 85
the rest without errors --> 80
Late submission or submission with error --> 60

Implementing a Library Catalog System - a console-based application that demonstrates:
  1. Object-Oriented Programming (OOP) - Creating and using a Book class
  2. Encapsulation - Using getter methods to access private attributes
  3. CRUD Operations - Create (add books), Update (borrow/return), Read (display books)
  4. Menu-driven Interface - User interaction via numbered choices
  5. Input Validation - Error handling for invalid inputs and out-of-range indices
  6. Collection Management - Storing objects in a list and manipulating them

This is a practical exercise for learning:
  1. Class design and instantiation
  2. Method creation and calling
  3. List operations with custom objects
  4. User input handling in Python
  5. Basic error handling (try-except)
# oop_encapsulation_car_library.py
Implementing Object-Oriented Programming (OOP) concepts in Python, specifically focusing on:
1. Access Modifiers/Encapsulation - Demonstrating protected (_) and private (__) attributes/methods in a Car class
2. Understanding a Programming Assignment - You've been given a Library Catalog System activity (Activity 1) with clear requirements to:
	2.1 Build a Book class with encapsulation
	2.2 Implement a console-based library management system
	2.3 Handle book borrowing and returning functionality
	2.4 Submit with GitHub link and screenshots
3. Language Used
	3.1 Python 3 (using classes, methods, encapsulation conventions)
4. Technical Stacks
	4.1 Core Python 3 - No external libraries
	4.2 Concepts demonstrated: OOP, encapsulation, name mangling, getter patterns
	4.3 Input/Output: print(), input() (needed for the assignment)
