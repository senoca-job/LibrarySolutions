# Library Solution SDJ
Library Solution SDJ is application developed by a team of two students (including me), as part of my final project in my CFGS in Multiplataform Software Development.

This software is a multiplataform tool developed for the administration of book libraries. It is powered by a server developed in Java, that communicates to the clients throught the network using sockets. All communications between client and server are encrypted. The data is stored in a PostgresSQL database using JDBC.

My partner developed the client side, based on Android, using Kotlin and Jetpack Compose. This repo only includes my part (the server), but has a fully funcional CRUD that can be tested using the demos provided in my files.

## Technologies used
- Java
- PostgresSQL
- SQL
- JDBC
- Network communication using sockets
- Encryptation and deencryptation of data

## Installation
1. Clone repository.
2. Open the project with a Java IDE.
3. Install the database into PostgresSQL using the .sql files provided
4. Compile, and execute the program from the Java IDE, or through the command console.
