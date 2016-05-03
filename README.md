# ProductSelection

Prequesties:
1. Java 1.8
2. Maven 3

Setup Java / Maven environment before running the application.

ProductSelection application is a spring mvc web application to get the product based on the customerId assoicated to locationid.

1. CustomerLocationService - Returns locationId based on the customerId
2. CatalogueService - Returns the list of CategoryMapData object.
3. CustomerLocationTestData - Contains the customer test data.
4. CatalogueTestData - Contains category mapping test data.


Run the application:

1. mvn clean install tomcat:run
2. Open browser http://localhost:8080
3. Enter customerId starting either '110000' for LIVERPOOL & '220000' for LONDON locations.
