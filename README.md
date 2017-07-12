Libreoffice Calc Tutorials Image
============================

#### Building an image
```
$ docker build -t sampige-libreoffice-calc .
```

#### Running the container
```
$ docker run --name s-libreoffice-calc -p 8080:80 -d sampige-libreoffice-calc
```

### Stopping the container
```
$ docker stop s-libreoffice-calc
```
