# DIGITAL LIBRARY MANAGEMENT
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The main objective of this project is to provide a complete automated Library by digitizing its each and every functionality. Starting from the book-keeping, issuing of books, fine generation, advance booking and report generation all will be accomplished under one single project. The project will be a web based project with a database server responsible for maintaining every single detail of the Library. It has a very user friendly interface which can easily be operated by any non-technical person.
***
### REQUIREMENTS
1. <a href="https://www.oracle.com/in/java/technologies/javase/javase8-archive-downloads.html">JDK 8</a>
2. <a href="https://tomcat.apache.org/download-90.cgi">Tomcat Server v9.0</a>
3. <a href="https://www.oracle.com/in/database/technologies/oracle-database-software-downloads.html#db_ee">Oracle Database Software</a>
4. <a href="https://download.oracle.com/otn-pub/otn_software/jdbc/233/ojdbc8.jar">Oracle JDBC Driver</a>
5. <a href="https://www.eclipse.org/downloads/packages/installer">Eclipse IDE</a>
***
### MODULES

There are essentially two modules of this software:

1. <b>Admin module: </b>Admin will have complete control over the system. Admin has permissions to update, delete or modify any existing record or make a new entry (books and members).

2. <b>Users: </b>The normal users enjoy only limited privileges. They have a view access to the books. They can browse through the categories, search for a particular book, return and issue a book. They are also provided with an email option in case of a query.
***
### how to run ?
<b>STEP-1:</b>&nbsp; Go to <b>Window Search Bar</b> And search <b>Services</b>, Then find <em>"Apache Tomcat v9.0"</em> and <em>"OracleServiceXE"</em>. Start both the services to run the Tomcat Server and Oracle Database.

<b>STEP-2:</b>&nbsp; Open your browser and enter the following URL to login to your Oracle Database.
~~~
http://localhost:<port number assigned during installation>/apex/
~~~
&nbsp;&nbsp;&nbsp;In my System it is: 
~~~
http://localhost:8000/apex/
~~~

<b>STEP-3:</b>&nbsp; Login with your Username and Password to manage your Database. For this project it is <a href="" target="_blank">here</a>.

<b>STEP-4:</b>&nbsp; Open a new tab in browser and enter the following URL to login to your Tomcat Server.
~~~
http://localhost:<port number assigned during installation>/
~~~
&nbsp;&nbsp;&nbsp;In my System it is: 
~~~
http://localhost:8080/
~~~
<b>STEP-5:</b>&nbsp; Login with your Username and Password to manage your Server Configuration.

<b>STEP-6:</b>&nbsp; Tomcat Server pages are stored in its <em>webapps</em> folder in its installation path. In that folder each folder consist of one or more webpages.

&nbsp;&nbsp;&nbsp;In my System installation path is:
~~~
C:\Program Files (x86)\Apache Software Foundation\Tomcat 9.0\webapps
~~~
<b>STEP-7:</b>&nbsp; Place your project folder in the above mentioned path.

<b>STEP-8:</b>&nbsp; Open a new tab in browser and enter the following URL to open your webpage. if any error ocuurs then restart the Tomcat server as done in <b>STEP-1</b>.
~~~
http://localhost:<port number assigned during installation>/<project_foldername>/
~~~
&nbsp;&nbsp;&nbsp;For this project it is: 
~~~
http://localhost:8080/library1/
~~~
<b>STEP-9:</b> <em>Now you have successfully hosted your java web application.</em>
