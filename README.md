# ailys_test
Ailys test 

1. activate Docker
```
docker run --rm -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/scipy-notebook
```

2. http://localhost:10000