create env

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create a req file 

install the req
```bash
pip install -r requirements.txt
```
```bash
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


onlinear updates for readme
```bash
git add . && git commit -m "update README.md"
```

```bash
git remote add origin https://github.com/PrajjwalSule21/simple-dvc-demo.git
```

```bash
git branch -M main
```

```bash
git push origin main
```