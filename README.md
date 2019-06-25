[Install Docker on macOS](https://runnable.com/docker/install-docker-on-macos)

[Install Docker on Windows 10](https://runnable.com/docker/install-docker-on-windows-10)

[Install Docker on Windows 7 or 8](https://docs.docker.com/toolbox/toolbox_install_windows/)

### To run the Dockerhub image:

```
docker pull spurawat/django-firstapp
docker run -p 8000:8000 spurawat/django-firstapp
```

You should now be able to go to

```
http://localhost:8000
```

### To run the code locally through Docker:

Clone the repo

```
git clone https://github.com/krmarcus-ucsd/flask-ml-example.git
cd flask-ml-example
```

```

Build and run Docker image

``
docker-compose up
``

You should now be able to go to

```
http://localhost:8000
```

