# Building Java Application with Gradle.  
This is a simple Java application build and run using **Maven**.
## Step 1: Clone the repository.
```bash
$ git clone https://github.com/Ibrahim-Adel15/build2.git
```
<img width="800" height="210" alt="clone src code" src="https://github.com/user-attachments/assets/80bf8920-4728-43e5-a7dd-e425615af120" />


## step 2: Run Unit test.
Unit tests verifies functionality

```bash
$ mvn test
```
<img width="800" height="747" alt="test" src="https://github.com/user-attachments/assets/1384cecc-89d5-422e-a923-369300a7d16b" />

## step 3: Build the Application.
Build the JAR artifact with Maven.
```bash
$ mvn package
```
<img width="800" height="791" alt="package" src="https://github.com/user-attachments/assets/03b408a8-bf50-425d-b3c0-b579caf614e4" />

## step 4: Run the Appliction.
```bash
$ java -jar ~/build2/target/hello-ivolve-1.0-SNAPSHOT.jar
```
<img width="800" height="71" alt="run locally" src="https://github.com/user-attachments/assets/154c3f2a-c5fa-4e85-b553-c7b8cbc70abb" />

## Summary
The full workflow of using Gradle to build and run Application:
-  Clone the repository from Github.
-  Run Unit test to ensure functions behave as expected.
-  Build the JAR artifact with Maven.
-  Running the Appliction and verifying that it is running.
