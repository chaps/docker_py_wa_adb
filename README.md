# Python Whatsapp Adb Docker Files

## python_adb

Base python:3.6 image
with adb installed.

### Build PythonAdb Docker image from source:

```
docker build -f PyAdbDockerfile -t chaps/python_adb .
```

### Pull from dockerhub:
```
docker pull chaps/python_adb
```

### Run python_abd:

```
docker run -it -d chaps/py_adb
```


### Build PythonWaAdb Docker image:

```
docker build -f PyWaAdbDockerfile -t chaps/py_wa_adb .
```

### Pull from dockerhub:
```
docker pull chaps/py_wa_adb
```

### Run py_wa_adb:
```
docker run -it -d chaps/py_wa_adb
```