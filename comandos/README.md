# Iniciar o projeto Django

python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact


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

# acada nova alteração no projeto
# refazer
git init
git add .
git commit -m 'Mensagem'
# e pra subir tudo -> - '-u' somente na primeira vez pra setar como padrão 
git push origin main -u 

# o URL_DO_GIT é o próprio link do repositório criado anteriormente
