Libreoffice Tutorials Image
============================

#### Building an image
```
$ docker build -t sampige-libreoffice .
```

#### Running the container
```
$ docker run --name s-libreoffice -p 8080:80 -d sampige-libreoffice
```

### Stopping the container
```
$ docker stop s-libreoffice
```
