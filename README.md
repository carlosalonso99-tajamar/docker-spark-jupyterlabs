```
docker build -t jupyterlab_spark .
```

```
docker run -it --name spark-container -p 8888:8888 jupyterlab_spark
```
