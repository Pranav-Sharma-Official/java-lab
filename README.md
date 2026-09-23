# Java Projects Collection

A collection of Java projects, practical programs, JDBC applications,
RMI examples, Servlet/Tomcat work, and supporting Java development
tools.

## 📁 Repository Structure

``` text
java_projects/
│
├── javalab/
│   └── Java laboratory programs and OOP-based examples
│
├── my Sql connect jdbc/
│   └── MySQL connectivity project using Java JDBC
│
├── RMI java/
│   └── Java RMI client-server example
│
├── server client/
│   └── Java socket-based server-client programs
│
├── Student Registration Form/
│   └── Java-based Student Registration Form application
│
├── mysql-connector-j-26.7.0/
│   └── MySQL Connector/J library and source distribution
│
└── apache-tomcat-11.0.25/
    └── Apache Tomcat 11 server and web applications
```

## 🚀 Projects

### 1. Java Lab

The `javalab` folder contains Java laboratory programs and examples
covering core Java concepts such as:

-   Classes and Objects
-   OOP concepts
-   Model/View/Controller-style structure
-   Java program execution
-   `.java` and compiled `.class` files

This section can be used for practicing Java fundamentals and college
laboratory programs.

------------------------------------------------------------------------

### 2. MySQL Connect JDBC

The `my Sql connect jdbc` project demonstrates database connectivity
between Java and MySQL using **JDBC (Java Database Connectivity)**.

**Technologies:**

-   Java
-   JDBC
-   MySQL
-   MySQL Connector/J

**Typical workflow:**

``` text
Java Application
      ↓
     JDBC
      ↓
MySQL Connector/J
      ↓
    MySQL
```

The project contains source code, compiled classes, and the required
JDBC connector library.

------------------------------------------------------------------------

### 3. Java RMI

The `RMI java` project demonstrates **Java Remote Method Invocation
(RMI)**.

RMI allows a Java program to invoke methods on an object running in
another Java Virtual Machine.

**Main concepts:**

-   Remote Interface
-   Remote Object
-   RMI Server
-   RMI Client
-   Remote Method Invocation

**Basic architecture:**

``` text
Client
  │
  │ Remote Method Call
  ↓
RMI Registry
  │
  ↓
Remote Server Object
```

------------------------------------------------------------------------

### 4. Server Client

The `server client` project contains Java server-client communication
examples.

The project demonstrates concepts such as:

-   Client-server architecture
-   Network communication
-   Sockets
-   Input/output streams
-   Sending and receiving data

Basic architecture:

``` text
Client  ←──── Network Connection ────→  Server
```

------------------------------------------------------------------------

### 5. Student Registration Form

The `Student Registration Form` project is a Java-based registration
form application.

It demonstrates concepts such as:

-   GUI-based form handling
-   User input
-   Event handling
-   Java classes and objects
-   Database/JDBC integration where applicable

It can be extended with features such as student record insertion,
update, deletion, and search.

------------------------------------------------------------------------

## 🗄️ MySQL Connector/J

The `mysql-connector-j-26.7.0` directory contains **MySQL Connector/J**,
the JDBC driver used by Java applications to communicate with MySQL
databases.

It is used by projects such as:

``` text
Java Application
      ↓
JDBC API
      ↓
MySQL Connector/J
      ↓
MySQL Database
```

The directory contains the Connector/J distribution files, source files,
documentation, and the `.jar` library.

> Note: This directory is a dependency/library distribution rather than
> a standalone application project.

------------------------------------------------------------------------

## 🌐 Apache Tomcat 11

The `apache-tomcat-11.0.25` directory contains the Apache Tomcat 11
server.

Tomcat is used to run Java web applications such as:

-   Servlets
-   JSP applications
-   Web applications packaged as WAR files

Important directories include:

  Directory   Purpose
  ----------- ------------------------------------------
  `bin`       Startup and shutdown scripts
  `conf`      Server configuration
  `lib`       Server libraries
  `logs`      Server log files
  `temp`      Temporary files
  `webapps`   Deployed web applications
  `work`      Generated/compiled web application files

Typical Servlet application flow:

``` text
Browser
   ↓
Tomcat Server
   ↓
Servlet
   ↓
Java Application Logic
   ↓
Response
   ↓
Browser
```

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   **Java**
-   **JDBC**
-   **MySQL**
-   **MySQL Connector/J**
-   **Java RMI**
-   **Java Sockets**
-   **Servlets**
-   **JSP**
-   **Apache Tomcat**
-   **HTML/CSS/JavaScript** where applicable

------------------------------------------------------------------------

## 📚 Purpose of This Repository

This repository serves as a collection of Java development and college
practical projects. It is useful for:

-   Practicing Core Java
-   Learning OOP
-   Practicing JDBC and MySQL connectivity
-   Understanding client-server programming
-   Learning Java RMI
-   Working with Servlets and Tomcat
-   Maintaining college laboratory projects
-   Preparing Java projects for future development and placement
    practice

------------------------------------------------------------------------

## ▶️ Getting Started

### Clone the repository

``` bash
git clone https://github.com/gourav-swami/java_projects.git
cd java_projects
```

### Java Projects

Open the required project in an IDE such as:

-   IntelliJ IDEA
-   Eclipse
-   NetBeans
-   VS Code

Make sure Java/JDK is installed and configured.

### JDBC Projects

For MySQL-based projects:

1.  Install MySQL.
2.  Start the MySQL server.
3.  Configure the database credentials in the Java project.
4.  Add MySQL Connector/J to the classpath if required.
5.  Compile and run the application.

### Tomcat Projects

1.  Open `apache-tomcat-11.0.25`.
2.  Place the web application in the `webapps` directory if required.
3.  Start Tomcat using the scripts in `bin`.
4.  Open the application through the Tomcat server URL.

------------------------------------------------------------------------

## 👨‍💻 Author

**Gourav Swami**

GitHub: <https://github.com/gourav-swami>

------------------------------------------------------------------------

## 📌 Note

Some folders contain compiled `.class` files, libraries, server files,
or generated files because this repository is also maintained as a
practical/learning workspace.

For production projects, it is generally better to use a build system
such as Maven or Gradle and avoid committing generated build artifacts.
