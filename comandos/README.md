# Iniciar o projeto Django

python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .


# Configurar o git

git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main

# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
# git remote add origin URL_DO_GIT 
git remote add origin https://github.com/durvallins/projeto-agenda-django.git

# o URL_DO_GIT é o próprio link do repositório criado anteriormente
