##CRIAR AMBIENTE VIRTUAL PYTHON

Primeiro conferir se o python ta instalado
-> python --version

Na pasta do seu projeto criar o ambiente virtual
-> python -m venv venv

ATIVAR O AMBIENTE
Entrar na pasta do projeto
.\venv\Scripts\Activate.ps1

(ps1 = powershell)
(bat = cmd)
Porém o powersehll vem bloqueado
entrar no powershell admin
clicar com botao direito do mouse no icone iniciar

Dentro do powershell
o comando

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

Primeiro o ambiente e depois instalar o flask
-> pip instal Flask

desativar o ambiente virtual
deactivate

dependencias

aniso8601==8.1.0
attrs==20.3.0
click==7.1.2
flask-marshmallow==0.14.0
flask-restplus==0.13.0
flask-sqlalchemy==2.4.4
flask==1.1.2
itsdangerous==1.1.0
jinja2==2.11.2
jsonschema==3.2.0
markupsafe==1.1.1
marshmallow-sqlalchemy==0.24.1
marshmallow==3.9.1
pyrsistent==0.17.3
pytz==2020.4
six==1.15.0
sqlalchemy==1.3.20
werkzeug==0.16.1
zipp==3.4.0