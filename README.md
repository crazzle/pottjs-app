NodeJS with Docker
============

This project is a small NodeJS application that can be deployed as a Docker container. It is based on the example at [nodejs.org](http://nodejs.org/).
This project is used as an example for the [pottjs-vagrant](https://github.com/crazzle/pottjs-vagrant) project.

Build application Docker image
-----------

```bash
docker build -t my_node_example .
```

Run application as Docker container
--------------

```bash
docker run -p 8080:8080 my_node_example
```
