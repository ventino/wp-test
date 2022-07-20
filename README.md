## Updated images for workpress testimg

Original work:

```
https://github.com/tfirdaus/wp-docklines
```

this image is used by bitbucket pipeline, to update it use:

```
docker build -t mcsaky/wp-test:8.1.6-fpm-alpine php8.x/fpm-alpine/
```

and

```
docker push mcsaky/wp-test:8.1.6-fpm-alpine
```

TODO: move the image in foodspring docker repo and build it from pipeline

