First Spring Boot Web Project – Vistula University

This project is a basic Spring Boot web application developed as part of a Java programming course at Vistula University. The main goal of the project is to demonstrate how a Spring Controller integrates with the Thymeleaf template engine to render dynamic web pages.

Technologies Used

•⁠  ⁠*Java 21* – Core programming language
•⁠  ⁠*Spring Boot 4.0.1 (SNAPSHOT)* – Framework for building the web application
•⁠  ⁠*Thymeleaf* – Server-side Java template engine for rendering HTML pages
•⁠  ⁠*Maven* – Used for project build and dependency management
•⁠  ⁠*Lombok* – Helps reduce boilerplate code

Setup and Installation

1.⁠ ⁠*Clone the Repository*
   Download or clone this project from GitHub.

2.⁠ ⁠*Open in an IDE*
   Import the project into IntelliJ IDEA or any preferred Java IDE.

3.⁠ ⁠*Install Dependencies*
   Maven will automatically download all required libraries (Spring Web, Thymeleaf, etc.).

4.⁠ ⁠*Run the Application*
   Execute the ⁠ main ⁠ method in ⁠ FirstProjectJavaSpring1Application.java ⁠.

5.⁠ ⁠*Access the Application*
   Open your browser and navigate to:
   [http://localhost:8080/greeting](http://localhost:8080/greeting)

How It Works

The application currently listens on the ⁠ /greeting ⁠ endpoint:

•⁠  ⁠*Static Display*
  Displays "Hello Vistula" or "Hello World" depending on the configuration in ⁠ greetings.html ⁠.

•⁠  ⁠*Dynamic Greeting*
  You can customize the greeting using the ⁠ name ⁠ parameter.
  Example:
  [http://localhost:8080/greeting?name=Umud](http://localhost:8080/greeting?name=Umud)
  This will display: *Hello Vistula Umud*

Project Structure

•⁠  ⁠HelloController.java – Handles incoming web requests and prepares data for the view
•⁠  ⁠greetings.html – Thymeleaf template located in ⁠ src/main/resources/templates/ ⁠
•⁠  ⁠pom.xml – Contains project configuration and dependencies

Created for educational purposes at *Vistula University*.

Author: Umud Kalbizada

![copy_4B4B162F-8477-46CD-A30E-725D51426A52](https://github.com/user-attachments/assets/8573be46-d962-45da-8819-a289602bc63e)
