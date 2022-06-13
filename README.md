
# Insurance Fraud Detecion

Machine Learning application to detect if an insurance claim is fraudulent or not




## 🔗 Project Links
Check out the deployed app [here](https://duplicate-question-pair.herokuapp.com/)

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
```javascript
import requests
res = requests.post('https://duplicate-question-pair.herokuapp.com/predict_duplicates', json={"question1" : ["Will AI be in demand in future ?"]})
if res.ok:
    print(res.text)
else :
    print(res)
```

