tutorial: https://spring.io/guides/gs/producing-web-service/


1. Generate web-service classes:
    mvn clean jaxb2:xjc


See generated WSDL:
    http://localhost:8080/ws/countries.wsdl

To test web-service run in command line:
    curl.exe --header "content-type: text/xml" -d @requestByCountry.xml http://localhost:8080/ws