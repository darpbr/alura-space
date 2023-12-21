# Desenvolvendo Python com Django

## Configurar projeto com framework Django

pip install Django

`django-admin help` -> Exibe todos os comandos que podem ser utilizados com django

`python manage.py help` -> Exibe os comandos que podemos rodar com o manage

- autenticação
- senhas
- banco de dados
- app (funcionalidades da aplicação)

Iniciar um projeto
`django-admin statrproject setup .`

Subindo o servidor

`python manage.py runserver`

Iniciar um app

`python manage.py startapp galeria`

alterar o **setup/settings.py** incluindo o app criado na lista de **INSTALLED_APPS**

## Dicas de boas práticas

1. Cada app deve ter sua própria lista de urls, evitando assim popular a lista de urls de setup
