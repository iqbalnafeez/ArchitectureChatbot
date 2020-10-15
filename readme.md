# Instalacion

https://rasa.com/docs/rasa/installation<br>

## MacOS y Ubuntu
`virtualenv env -p python3`<br>
`source env/bin/activate`<br>
`pip install rasa==2.0.0rc1`<br>
`pip install -U rasa-x==0.33.0rc1 --extra-index-url https://pypi.rasa.com/simple`<br>

## Windows
`pip3 install -U pip` <br>
`python3 -m venv ./venv`<br>
`.\venv\Scripts\activate`<br>
`pip install rasa==2.0.0rc1`<br>
`pip install -U rasa-x==0.33.0rc1 --extra-index-url https://pypi.rasa.com/simple

# Development
```
git pull
.\venv\Scripts\activate o source ./env/bin/activate
rasa train
rasa shell
deactivate ( o version windows ??)
```

# Git
```
git pull
git status
git add (lo del status)
git commit -m "mensaje de commit" 
git push 
```
