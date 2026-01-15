# Run Java Spring Boot App in a Container

This demo illustrates how to build and run a Java Spring Boot application inside a Docker container using Maven.
This approach is used for demonstration purposes only. In real-world production environments, a multi-stage Docker build is preferred to reduce image size and improve security.


## step 1: Writing the Dockerfile.

After cloning the application source code from GitHub, we write a Dockerfile to build and run the Java application inside a Docker container.

<img width="600" height="246" alt="Dockerfile" src="https://github.com/user-attachments/assets/c00a4636-8395-4991-a3a2-86dd52a8e9cb" />

## step 2: Build the image.

```bash
$ docker build -t lab3 .
```

After the image is built, we can notice that the image size is relatively large because the application is built inside the same image using Maven.

<img width="800" height="195" alt="image-size" src="https://github.com/user-attachments/assets/6fb586c2-9ec7-4865-9419-efa4cb5cc3b9" />

## step 3: Run the container.

We map the container’s port 8080 to port 8081 on the host.

```bash
$ docker run -d -p 8081:8080 --name container1 lab3
```

<img width="800" height="230" alt="run-container" src="https://github.com/user-attachments/assets/23007f9c-4146-48d2-a5dd-ac33dbf8a02c" />

## step 4: Test the application.

Test that the application is running.

```bash
$ curl localhost:8081
```

<img width="800" height="105" alt="test-app" src="https://github.com/user-attachments/assets/8e8e8e2b-c1c2-4b31-89d6-0f2244c64196" />

## step 5: Stop and delete the container.

```bash
$ docker stop container1 
```

<img width="800" height="252" alt="stop-container" src="https://github.com/user-attachments/assets/2678ad96-5ba5-4392-999e-e9d7b9d7aa2c" />

```bash
$ docker rm container1 
```

<img width="800" height="97" alt="delete-container" src="https://github.com/user-attachments/assets/6ecbb687-84b1-43d1-b74c-4d5a15761a42" />



