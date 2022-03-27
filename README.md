# Simple Flask App

- W projekcie wykorzystamy terminal Pycharm, dla utworzenia hermetycznego środowisko dla aplikacji:

  ```
  # tworzymy hermetyczne środowisko dla bibliotek aplikacji:
  $ python -m venv .venv

  # aktywowanie hermetycznego środowiska
  $ py -3 -m venv venv
  $ venv\Scripts\activate
  $ pip install Flask
  $ export FLASK_APP=main.py
  $ python main.py
  #  Running on http://127.0.0.1:5000/

  # zobacz
  $ pip list
  ```
