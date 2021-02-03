# avatar-app

# Watch the tutorial video

[How to build an Avatar maker app | Streamlit #18](https://youtu.be/4UCfxvURjgI)

<a href="https://youtu.be/4UCfxvURjgI"><img src="http://img.youtube.com/vi/4UCfxvURjgI/0.jpg" alt="How to build an Avatar maker app | Streamlit #18" title="How to build an Avatar maker app | Streamlit #18" width="400" /></a>

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

Install libcairo2
```
sudo apt-get install libcairo2
```

###  Launch the app

```
streamlit run app.py
```
