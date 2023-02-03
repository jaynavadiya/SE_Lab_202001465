# SE_Lab_202001465

# Lab-1_202001465

# IT314-Software Engineering Lab-1

## Identifying Functional and Non-Functional Requirements

### Q.1. Identify Functrional Requirements and Non-Functional Requirements:

### Functional Requirements:

#### Abstract: searching books and various parameters; exclusivity of borrowing the books ; username and password of the user and strong password requirements; book's location; librarian's permission for borrowing the book; displaying information about a book; history of books borrowed by a user; notification of overdue books to both the users and the librarian; admin portal; Non-member browsing; Web application only usable inside the institute LAN (Local Area Network)

- The user should be able to search for books in the library using criteria such as the title, author, publication date, etc., depending on their needs.
- The system should not provide the user the option to borrow a book if it has already been taken out by another user and should instead inform the user that the book has already been checked out by others.
- When a user wants to issue the book, the system should prompt them for their username and password. The system determines whether the entered information is correct, such as whether the password is entered correctly or whether the entered username is valid.
- The system should display the book's location in the library after it had been borrowed.
- Only if the user is a member of the system should the LIS (Library Information System) allow the user to borrow a book or return it if it has already been borrowed. Once a librarian acknowledges a user's request to borrow a book, the user is then able to do so.
- A system need to display all the essential information about the book.
- If a user requests a list of the books they have presently borrowed, books they have previously borrowed, the date they were borrowed, and the books they have returned, the system should display this information for that user.
- System should notify the user and librarian of the overdue books and calculate the fine for the overdue books when they are returned.
- When a new book is purchased, a system should enable the librarian to add a new record, or remove a record if a book is taken off the shelf, as and when necessary. 
- Admin Portal: The librarian should have administrative privileges and complete control over the system, including the ability to enter new book records and remove existing records.
- Non-Member Browsing: Non-members should be able to use the system to browse and search books online, but only members should be able to borrow and return books.
- Web Application: The final deliverable should be a web application that is accessible only within the institute LAN. This reduces the security risk of the software and ensures that confidential information is protected.

### Non-functional Requirements:
#### Abstract: Security; Storage; Capacity; Performance; Cost; Interoperability; Flexibility; Disaster Recovery; Accessibility; Maintanibility; Portability; Reliability; Scalability; Accuracy.

- Security:  The system should be secure, and confidential information, such as passwords, should not be stored in plain text to reduce the risk of unauthorized access. AES (Advanced Encryption System) should be added to make the system more secure.
- Storage: The data about book, user and admin (librarian) should be stored in a robust database (Postgresql or MongoDB).
- Capacity: The LIS should be able to handle atleast 1500 requests at a time. Different servers to be used for deploying the web application for less down time. 
- Performance: The LIS should respond to the requests within 250-500ms. 
- Cost: The web application should be made by using minimum budget and better cost choices should be made. The servers should not cost more than 50k INR per month.
- Interoperability: The LIS should store data in a timely manner and in case of any future needs, the data should be retreived easily saving time of both users and admin.
- Flexibility: The LIS should ensure the user can easily access key information. Everyone (the librarian and the users) should be able to understand the user interface (UI). The LIS can be made available in multiple languages for different set of users.
- Disaster Recovery: The LIS must not be down for more than 2 hours for any reason. Robus infrastructre should be used to deploy the web application and alternative deployments should be made in case of durability issues.
- Accessibility: The system should be accessible only within the institute LAN for security reasons, as this reduces the risk of unauthorized access from outside the network.
- Maintainability: The system should be as simple to update as possible. Even if changes are made, the current system should continue to function properly. The system should function properly in the event that additional features are necessary to be added.
- Accessibility - The database can be used on systems other than the one in which it was originally built.
Reliability: System should be reliable and accessible throughout the entire time the library is open. At this crucial time, the system shouldn't experience any failure.
Scalability: The system must function correctly and without error when a large number of users access it. The servers should be updatable in case of increase of users.
- Accuracy - The system must make sure that the information maintained regarding the books and the calculations of the penalties is accurate and consistent.

### Q.2. Identify scope, features and non-functional aspects of the following problem.

### Scope of the problem:

### Features of the problem:

### Non-functional aspects of the problem:
