# To build docker

```
docker build -t rails-toolbox -f Dockerfile.rails .
```

# To create new rails image

```
docker run -it -v $PWD:/opt/app rails-toolbox rails _7.0.4.3_ new sample_app -d mysql --skip-bundle
```


