# Building Java Application with Gradle.  
This demo illustrates how to use Gradle to test and run a simple Java application.

## Step 1: Clone the repository.
```bash
$ git clone https://github.com/Ibrahim-Adel15/build1.git
$ ls
```
<img width="800" height="316" alt="clone repo" src="https://github.com/user-attachments/assets/fa078332-dc20-4054-8870-99743a531a6a" />

## step 2: Run Unit test.
Unit tests help detect bugs early and ensure individual units behave as expected.

```bash
$ gradle test
```
<img width="800" height="232" alt="test" src="https://github.com/user-attachments/assets/304ded44-a69b-41ba-bf8c-9c94effc7e8b" />

## step 3: Build App (Generate Artifact).
An artifact is the output file of the build process that is ready for deployment.
```bash
$ gradle build
```
<img width="800" height="231" alt="image" src="https://github.com/user-attachments/assets/c29a5174-0704-4590-a7dd-9b117b5136e3" />

## step 4: Run the Appliction.
```bash
$ java -jar ~/build/libs/ivolve-app.jar
```
<img width="800" height="142" alt="image" src="https://github.com/user-attachments/assets/8ca10a0b-97b7-4616-a31e-2be7ef40bdc8" />


## Summary
The full workflow of using Gradle to build and run Application:
-  Clone the repository from Github.
-  Run Unit test to ensure functions behave as expected.
-  Build the JAR artifact with Gradle.
-  Running the Appliction and verifying that it is running.

