# Django CRUD Exemplo 

O seguinte projeto em Django mostra as funcionalidades do CRUD , onde principalmente se trabalha com vistas baseadas em funções:

- books\_fbv\_user: add user interaction to books\_fbv example.

## Instale os pacotes necessários

O projeto atual Django CRUD só precisa de um único pacote Python "Django", ele foi construído e testado com a versão Django 2.x. Para instalá-lo, use o seguinte comando:

    pip install -r requirements.txt


Django 2 requer Python 3, se você precisar de ajuda para configurar Python 3 em sua máquina, você pode consultar a excelente documentação DigitalOcean sobre
[Como instalar e configurar um ambiente de programação local para Python 3] (https://www.digitalocean.com/community/tutorial_series/how-to-install-and-set-up-a-local-programming-environment- for-python-3)

## Executando o aplicativo

Antes de executar o aplicativo, precisamos criar as tabelas de banco de dados necessárias:

    ./manage.py migrate

Agora você pode executar o servidor de desenvolvimento da web:

    ./manage.py runserver

Para acessar no aplicativo vá para o URL <http://localhost:8000/>


## Preciso de um usuário e senha para acessar "books\_fbv\_user"

Sim, os "books\_fbv\_user" demonstram como CRUD pode funcionar com usuários Django, e você precisa criar um usuário para testá-lo,
você pode criar um usuário usando o seguinte comando:
    ./manage.py createsuperuser

Para criar um usuário normal (não superusuário), você deve fazer login na página de administração e criá-lo
: <http://localhost:8000/admin/>
