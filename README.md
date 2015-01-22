Java Persistence - Module 1 - Basic Mapping – Practice

1. Prepare a new project with JPA inside. Call it CarManagement.

2. Create entity Car with the following fields: Long id, String model, Integer power.

3. Create embeddable value type Engine with the following fields: String model, Integer volume. 

Include it to the Car entity.

4. Test basic read-write operations with the Car entity.

5. Add new fields to the Car and Engine classes at your discretion. Try to use following annotations:

b. SecondaryTable

e. Enumeration (for example create CarType enum)

f. Convert (create some Converter)

6. Create the following successors for the Car class: ElectricCar, OilCar, and HybridCar. Add some 

specific fields for them. Try to use all three types of inheritance mapping. 

7. [Optional] Try to use both MySQL and PostgreSQL databases and both Hibernate and EclipseLink 

8. [Optional] Connect the object model and the tables via pure JDBC. The connection means simple 

CRUD operations.
