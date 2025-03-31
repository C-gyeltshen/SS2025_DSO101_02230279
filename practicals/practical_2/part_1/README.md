# Practical 2 Part 1 

## Introduction
## Procedures and Results

### **Step1. Building Docker image for both services**

- Docker image for nginx service
  ```sh
  docker build -t nginx .
  ```
  ![nginx-image](./assets/build-nginx.png)

- Docker image for nodejs service
  ```sh
  docker build -t web .
  ```
  ![web-image](./assets/build-web.png)

  ![images](./assets/ls.png)

### **Step2. Creating a network for containers to communicate**

```sh
docker network create sample-netwrok
```
![network](./assets/sub-net.png)

### **Step3. creating container with specific configuration**



