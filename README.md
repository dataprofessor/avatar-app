# avatar-app

# Demo

[Demo of this web app]().

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *avatar*
```
conda create -n avatar python=3.7.9
```
Secondly, we will login to the *avatar* environement
```
conda activate avatar
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/avatar-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Launch the app

```
streamlit run app.py
```
