# python-template

Shorten shell prompt
```
PS1="$: "
```

Project set up using following commands
```
     mkdir git
     cd git
     git clone https://github.com/harjeet88/python-template.git - new empty git
     ls
     cd python-template
     python3 -m venv myvenv
     ls
     source myvenv/bin/activate
     pip install flask pytest
     pip freeze > requirements.txt
     ls
     mkdir src
     cd src
     touch app.py
     vi app.py -- write contents
     python3 app.py
     cd ..
     mkdir tests
     cd tests
     touch test_app.py
     vi test_app.py
     cd ..
     ls
     export PYTHONPATH=src
     echo $PYTHONPATH
     pytest
     pytest -v
     vi .gitignore
     git status
     git add .
     git status
     git commit -m "files created"
     git config --global user.email "harjeet.kumar24@gmail.com"
     git config --global user.name "harjeet88"
     git commit -m "files created"
     git push
     git push
     python --version
```
