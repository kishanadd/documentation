# documentation

JDBC Resoures file :
 <Resource name="jdbc/TestDB" auth="Container" type="javax.sql.DataSource"
               maxTotal="100" maxIdle="30" maxWaitMillis="10000"
               username="javauser" password="javadude" driverClassName="com.mysql.jdbc.Driver"
               url="jdbc:mysql://localhost:3306/javatest"/>
change localhost to local IP 

JDBC Driver link : 
 wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-java-5.1.46.tar.gz
