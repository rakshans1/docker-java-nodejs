[![Travis](https://img.shields.io/travis/rakshans1/docker-java-nodejs.svg)](https://travis-ci.org/rakshans1/docker-java-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/java-nodejs.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/java-nodejs/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/java-nodejs/latest.svg)]()


![rakshans1/java-nodejs](/icon.png?raw=true)
# Latest Java with Node.js v8 and npm
### based on [Java 8 (1.8.0_111)](https://github.com/rakshans1/docker-java)
----
### Pull from Docker Hub
```
docker pull rakshans1/java-nodejs:latest
```

### Build from GitHub
```
docker build -t rakshans1/java-nodejs github.com/rakshans1/docker-java-nodejs
```

### Run image
```
docker run -it rakshans1/java-nodejs bash
```

### Use as base image
```Dockerfile
FROM rakshans1/java-nodejs:latest
```