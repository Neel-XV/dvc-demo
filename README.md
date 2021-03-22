create env

conda create -n wineq python=3.7 -y

activate env

pip install -r requirements.txt

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"
