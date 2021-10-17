
create env
```bash
conda create -n ./envs python=3.7 -y
```

activate env
```bash
conda activate ./envs
```

created a req file

install the req
```bash
pip install -r requirement.txt
```

downloaded the data from below link (winquality)
```bash
https://raw.githubusercontent.com/mlflow/mlflow-example/master/wine-quality.csv
```
``` bash
git init
```

```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

```bash
git add .
```

```bash
git commit -m "first commit"
```