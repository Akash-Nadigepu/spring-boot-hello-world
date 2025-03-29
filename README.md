# **Dockerizing a Java Application and Deploying it on Kubernetes**

## **Overview**
This guide covers the process of containerizing a Java application using Docker and deploying it on a Kubernetes cluster.

**Author:** Akash Nadigepu  
**GitHub Repo:** [spring-boot-hello-world](https://github.com/Akash-Nadigepu/spring-boot-hello-world)  
**DockerHub Repo:** [akash6637/spring-boot-hello-world](https://hub.docker.com/repository/docker/akash6637/spring-boot-hello-world/general)

---

## **Steps**

### **Task 1: Fork and Clone Java Repository**
1. Forked the basic Hello-world Spring Boot repository  
   ![image](https://github.com/user-attachments/assets/92749726-b6bc-45b9-a252-ad7af1c7828e)

2. Cloned it into the local machine.  
   ![image](https://github.com/user-attachments/assets/35a961c7-a5f7-4132-b4ce-894cdeb61527)

---

### **Task 2: Define a Dockerfile**
1. Create a `Dockerfile` with the following content:  
   ![image](https://github.com/user-attachments/assets/98b3d1ba-c11b-4f8f-961e-dae3dbbf63d4)

---

### **Task 3: Build and Push Docker Image**

- **Build the Docker image:**  
  ![image](https://github.com/user-attachments/assets/02bac17b-22c8-412c-8ab0-cc8250d2b9b1)

- **Run the container locally:**  
  ![image](https://github.com/user-attachments/assets/325b3901-9d38-4dae-83ce-7d6b57c574f2)

- **Check if the container is running:**  
  ![image](https://github.com/user-attachments/assets/b0c76e56-6322-4435-8782-b8fd3a1bceb2)

- **Push the image to Docker Hub:**  
  ![image](https://github.com/user-attachments/assets/e129d944-20d2-4f76-9cce-f8cafd5ab0bf)  
  ![image](https://github.com/user-attachments/assets/46e3f929-ef82-4ba4-9768-9da3d2d55a4e)

---

### **Task 4: Create a Kubernetes Deployment**

- **Deployment Configuration:**  
  ![image](https://github.com/user-attachments/assets/e5696346-5546-4520-bfcb-341221ef89b4)  
  ![image](https://github.com/user-attachments/assets/c5815c7a-ec30-4f43-9829-362a5e8a1cd4)

---

### **Task 5: Scale Up and Scale Down**

- **Scaling the Deployment:**  
  ![image](https://github.com/user-attachments/assets/cbbddb4c-4d35-4056-b6b9-f4f196cc8fc4)

---

### **Task 6: Expose the Service Using NodePort**

- **Expose the service and retrieve NodePort:**  
  ![image](https://github.com/user-attachments/assets/9b88342b-6081-422f-ba5a-8d302861bd96)

- **Access the application:**  
  ![image](https://github.com/user-attachments/assets/b3131fa7-7a1f-451a-9995-9fc7b563ac13)

---

### **Task 7: Automate Deployment Using Jenkins**

- **Jenkins Pipeline Automation:**  
  ![image](https://github.com/user-attachments/assets/f3ab2e6c-2374-41ee-9386-a824cbdfb99f)  
  ![image](https://github.com/user-attachments/assets/92ffda22-5bd5-4c8e-9880-e971bbc5eeb5)

---


