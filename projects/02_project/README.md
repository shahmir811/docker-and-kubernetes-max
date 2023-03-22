## 02 Project

I have written a **Dockerfile** where I have run a simple nodejs application inside a single container. The nodejs application is using port 80

### Working with container

1 - You have to build an image with the Dockerfile. For this, you have to navigate in this folder and then execute below in the terminal:

```sh
docker build -t <IMAGE_NAME> .
```

2 - After building image, you can execute the following command in the terminal to run the container:

```sh
docker run --name <CONTAINER_NAME> -p 80:80 <IMAGE_NAME>
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
http://localhost:80
```

![02-project-docker](https://user-images.githubusercontent.com/19389145/225526095-eadaee4c-51dc-48c1-b2c9-676bd7374a6d.png)
