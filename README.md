# terrafic_management
this is a **provider** web-service which communicates with other web services and provides trafficing records for other web-services.
### language and technology
recommended programming language for this project is **java** since its a high level proggramming language and easy to implement but very fast and compilable.
it provides so many useful libraries which we can use and since our project is highly concerd about retrival time it can be a very good choice.
since its a provider we use **UDDI** and **WSDL** technologies for our web servic
### Database
a sql based data base such as **Mysql** is recommended since the system should bd online and it has many layers interacting with each other data are highly related to each other
like vehicle properties and previous records and current stats of passing vehicles which should be connected through a **DBMS** so a **relational** database is suitable
### functionality
since it very important to get the info in desired time and other services doesn't need to write anything on our web-service it is suitable and required for us to have an **asynchronous** functionality
### communication
we use **message broker** as a tool for communicatoin between our services since its very fast and is compatibale with many platforms and is based on jav which we are already using in this project
