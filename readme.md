Sample from https://habr.com/ru/post/429980/

``` shell
sudo apt-get update
sudo apt-get -y install imagemagick
PIPENV_VENV_IN_PROJECT=1 pipenv install --dev
pipenv run python lenin.py
```

![line.gif]
