
# Insurance Fraud Detection

Machine Learning application to detect if an insurance claim is fraudulent or not




## 🔗 Project Links
Check out the deployed app [here](https://insurancefrauddetection.azurewebsites.net)

## Run Locally

Clone the project

```bash
  git clone https://github.com/Hassi34/insuranceFraudDetection.git
```

Go to the project directory

```bash
  cd insuranceFraudDetection
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  flask run
```


## Usage/Examples 
## REST API
### Prediction
```javascript
import requests
res = requests.post('https://insurancefrauddetection.azurewebsites.net/predict', json={"filepath" : "Prediction_Batch_files"})
if res.ok:
    print(res.text)
else :
    print(res)
```

