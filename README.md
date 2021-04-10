# ailys_test
Ailys test 

1. Activate Docker:
```
docker run --rm -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/scipy-notebook
```

2. Navigate to: 
http://localhost:10000

3. Open the `Source code.ipynb` file and run the code.
4. In the end it should produce the merged CSV file and 2 Visualizations. 
5. Thank you for your time!