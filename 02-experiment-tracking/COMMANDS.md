### Creating  environment
```bash
python3 -m venv venv_mlops_week2
source venv_mlops_week2/bin/activate
pip3 install -r requirements.txt
```

### MLFLOW 
#### Open MLFLOW UI
```bash
mlflow ui
```
##### With SQLLITE
```bash
mlflow ui --backend-store-uri sqlite:///mlflow.db
```