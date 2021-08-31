create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```
create a req file

install the requirements
```bash
pip install -r requirements.txt
```
download the data from
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

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
```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/Harikantipudi/dvcdemo.git
git branch -M main
git push -u origin main
```