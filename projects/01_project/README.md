## 01 Project

I have written my first **Dockerfile** where I have run a simple nodejs application inside a single container. The nodejs application is using port 3000

### Working with container

1 - You have to build an image with the Dockerfile. For this, you have to navigate in this folder and then execute below in the terminal:

```sh
docker build -t <IMAGE_NAME> .
```

2 - After building image, you can execute the following command in the terminal to run the container:

```sh
docker run --name <CONTAINER_NAME> -p 3000:3000 <IMAGE_NAME>
```

3 - You can see the status of the containers by executing the following command in the another terminal tab:

```sh
docker ps -a
```

4 - Execute the following command in the terminal to stop the running container:

```sh
docker stop <CONTAINER_NAME>
```

5 - Visit the browser on the following link and you will get your node application:

```sh
http://localhost:3000
```
