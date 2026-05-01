This project uses docker to make sure that the notebook will run on any machine the same way. For more information on docker, visit [here](https://www.docker.com/)

To run it:
```
docker build -t my-notebook .
docker run -p 8888:8888 my-notebook
```

The first command builds an image of a container that will have its own kernal with all the dependencies that will sit on top of your machine without access to your files. Then once you run the container, it will be in an isolated Linux environment that will be serving the jupyter notebook as normal, which you can visit at http://localhost:8888. The `-p 8888:8888` essentially is telling your machine to map the containers port 8888 to your machine's 8888.
