### 3 ways to run the project

#### In development

1. In IDE: Clicking to run directly in the project

2. In terminal: Using Marwin wrapper
   MacOS:
   ```bash
   $ ./mvnw spring-boot:run
   ```
   Windows:
   ```bash
   $ mvnw spring-boot:run
   ```

#### In release

1. In terminal

   1.1) Build using Marwin wrapper:
   MacOS:

   ```bash
   $ ./mvnw package
   ```

   Windows:

   ```bash
   $ mvnw package
   ```

   1.2) Run on the jar file the got built

   ```bash
   $ java -jar ./target/demo-0.0.1-SNAPSHOT.jar
   ```
