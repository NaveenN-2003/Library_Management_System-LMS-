# 📚 Library Management System -Java





A Library Management System (LMS) designed using the principles of Object-Oriented Analysis and Design (OOAD). This project provides a comprehensive solution for managing library operations such as book management, member management, and transaction handling, all while maintaining a clean and user-friendly interface.

The system is built with a focus on scalability and maintainability, using object-oriented concepts to organize and manage the different components (e.g., books, members, transactions). The core logic is implemented in a modular and efficient manner, while the Graphical User Interface (GUI) is kept minimal to ensure ease of use without overwhelming the user.


## Key Features

*   Book Management: Add, delete, search, and update book information (title, author, publisher, etc.).

*  Member Management: Register new members, update member details, and track borrowing history.

*  Search Functionality: Quickly search books or members by various criteria.

*  Minimal GUI: Clean, simple interface that allows users to easily interact with the system while minimizing the amount of code used for the UI.





## CLASS DIAGRAM


The **Class Diagram** of the project is also provided along with the **Database Schema** file. The class diagram file can be opened using [Star UML](http://staruml.io/).

 

## Actors:
The actors include the following: 
* Librarian
* Checkout Clerk
* Borrower
* Administrator

## Use Cases:
After determining the actors, the second step in use case analysis is to determine the tasks that each actor will need to do with the system. Each task is called a use case because it represents one particular way the system will be used.

**In other words, only those use cases are listed that actors will need to do when they are using the system to solve the customer’s problem.** 

### Borrower:
* ❏ Search for items by title.
* ❏ ... by author.
* ❏ ... by subject.
* ❏ Place a book on hold if it is on loan to somebody else.
* ❏ Check  the  borrower’s  personal  information  and  list  of  books  currently
borrowed.

### Checkout Clerk:
* ❏ All the Borrower use cases, plus
* ❏ Check out an item for a borrower.
* ❏ Check in an item that has been returned.
* ❏ Renew an item.
* ❏ Record that a fine has been paid.
* ❏ Add a new borrower.
* ❏ Update a borrower’s personal information (address, telephone number etc.).

### Librarian:
* ❏ All of the Borrower and Checkout Clerk use cases, plus
* ❏ Add a new item to the collection.
* ❏ Delete an item from the collection.
* ❏ Change the information the system has recorded about an item.

### Administrator:
* ❏ Add Clerk.
* ❏ Add Librarian.
* ❏ View Issued Books History.
* ❏ View All Books in Library.












