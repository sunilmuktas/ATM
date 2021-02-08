# ATM
ATM demo
    
# atm
atm-documents


environment 
java 8 
maven

navigate until root dircetory : ATMDEMO-master

then below command

mvn clean install

java -jar target/AtmDemo-0.0.1-SNAPSHOT.jar

this application being configured Swagger where it is shows all rest API.


in order to see Swagger execute click on below URL 


http://localhost:9999/swagger-ui.html#/atm-controller/getAllATMSUsingGET


API :


get all ATM list :http://localhost:9999/atm/list


search based on city name :http://localhost:9999/atm/list/{​​​​​​​cityn}​​​​​​​
