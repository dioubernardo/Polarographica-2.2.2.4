Nova abordagem rodar com o python velho

- instalar pyenv
https://github.com/pyenv-win/pyenv-win/blob/master/docs/installation.md#powershell

- instalar python 3.7
```
pyenv install 3.7
```

- criar env
```
pyenv local 3.7
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

- rodando a aplicação
```
python Main_Window.py
```