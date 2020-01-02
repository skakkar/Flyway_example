# Flyway_example
Integration of SpringBoot with Flyway - a tool for database migration
Flyway is a database migration and versioning tool. Flyway comes with unique feature that you can write migration scripts not only in SQL format but also as Java code.
Using Java code, Complex and dynamic database migrations can be implemented. This feature should be used with caution, however, since the dynamic database migrations are hard to debug if anything goes wrong.

Followings are FLyway Commands:
- Migrate
- Info
- Validate
- Repair 
- clean

Flyway not provides any rollback feature however it simply says 'restore from backup if anything fails'.

Prerequisite:
- JDK 1.8 
- MAVEN
- ANY IDE (STS, IntelliJ, Eclipse, Visual Code etc.)

How to use this example:
1. Git clone https://github.com/skakkar/Flyway_example.git
2. Do mvn clean install
3. Check H2 Console to see DB changes


- If you wants to contribute to this simple example; Fork the branch and submit PR, after code review your changes will be included in this app.

