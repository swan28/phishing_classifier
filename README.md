# Phishing-Classifier

1. Create python virtual environment

```
    conda create -p .venv python==3.8 -y
```

2. Activate virtual environment
```
    conda activate
```

3. Install dependencies
``` 
    pip install -r requirements.txt
```

4. URL for predicting locally ---> upload the `phisingtest.csv` to get predicted results

```
    127.0.0.1:500/predict
``` 
5. OR this if deploying on cloud 
```
    0.0.0.0:500/predict
``` 