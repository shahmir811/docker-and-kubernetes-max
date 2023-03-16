### 01 Project

I have written my first **Dockerfile** where I have run a simple nodejs application inside a single container.

Working with container

1 - You have to build an image with the Dockerfile. For this, you have to navigate in this folder and then execute below:

```sh
docker build -t <IMAGE_NAME> .
```

2 - After building image, you can execute the following command to run the container:

```sh
docker run --name <CONTAINER_NAME> -p 3000:3000 <IMAGE_NAME>
```

3 - You can see the status of the containers by executing the following command:

```sh
docker ps -a
```

4 - Execute the following command to stop the running container:

```sh
docker stop <CONTAINER_NAME>
```
