# Login Credential Validation

**Introduction to JSP and Servlet-based Web Applications**

JavaServer Pages (JSP) is a technology used to create dynamic web content by using Java in combination with HTML. JSP allows for the embedding of Java code directly into HTML pages, providing a way to build interactive web applications. Servlets complement JSP by handling requests and responses in a Java web application, forming a powerful duo for building dynamic, server-side applications.

**Problem Statement: Login Credential Validation using JSP**

The objective is to design and develop a web application for login credential validation using JSP. The application will provide a login page for users to enter their username and password. If the user is new, they can register through a registration form. The application will validate login credentials, welcome the user upon successful login, and handle invalid login attempts by implementing a blocking mechanism after three failed attempts.

**Functional Requirements:**

1. **Login Page**:
   1. Display a form for users to enter their username and password.
   1. Provide a link or button for new users to access the registration form.
1. **Registration Form**:
   1. Allow new users to register by providing a username and password.
   1. Store the registration details in a database.
1. **Login Validation**:
   1. Validate the entered credentials against the stored data in the database.
   1. If credentials match, display a welcome message with the username.
   1. If credentials do not match, display "Invalid credentials" and redirect back to the login page.
   1. Track the number of invalid login attempts. If a user exceeds three invalid attempts, display a message "You have exceeded the attempt for today, try tomorrow" and block further attempts for that day.

I have attached the complete pdf, which is also the same file that I had submitted as an assignment for my college earlier this year. It illustrates everything in detail.

Hope you find it helpful!

