# ovinogest---base

Repositorio da base do projeto Ovinogest

Esses são apenas os arquivos base do projeto (apenas para substituir os antigos no seu projeto), para rodar o servidor e verificar a funcionalidade você precisa ter o projeto em um ambiente virtual e obviamente ter o projeto tbm já pré intalado. 

# Processo de criação do Projeto

Segue os comandos via terminal para a criação do ambiente virtual e do projeto:

===================================================================================

# Criação do Ambiente Virtual

Primeiro, precisa criar uma pasta:

> mkdir ovinogest
> cd ovinogest

Partindo para a criação do ambiente virtual:

> py -m venv myenv

Caso não dê certo, tente:

> python -m venv myenv

ou

> python3 -m venv myenv

Agora precisa entrar nesse ambiente virtual:

> myenv\Scripts\activate

Se der certo, o status do seu terminal deve ficar parecido com isso:

> (myenv) C:\ovinogest>

===================================================================================

# Instalação de pacotes

Ja dentro do ambiente, precisa instalar alguns pacotes nele para conseguir rodar o
projeto no estado atual:

------ Atualizar o pip ------ 

> pip install --upgrade pip

------ Instalar todos os pacotes python necessários ------
 
> pip install requests

------ Instalar o Django ------

> pip install django

------ Instalar o Pillow ------

> pip install pillow

===================================================================================

# Configurações do Django

Ja com os pacotes instalados, vamos para as configurações:

------ Startar o projeto ------

> django-admin startproject ovinogest

------ Startar o App da aplicação ------

> python manage.py startapp ovinogestApp

===================================================================================

# Criação de pastas adicionais (obrigatório)

Acesse a pasta ovinoApp e crie a pasta "templates":

> cd ovinoApp
> mkdir templates

Acesse a pasta e crie outra pasta chamada "ovino":

> cd templates
> mkdir ovino

Retorne ao diretório ovinoApp e crie a pasta "static":

> cd ..
> cd ..
> mkdir static

Acesse a pasta e crie a pasta "img":

> cd static
> mkdir img

===================================================================================

# Substituição dos arquivos

Após seguir esses passos, baixe os arquivos (settings.py e urls.py) da ramificação 
ovinogest nesse repositório do git e substitua na pasta ovinogest:

![image](https://github.com/user-attachments/assets/7067fdeb-232f-434f-a4c2-2025d6303345)

Também baixe os arquivos (forms.py , models.py  e views.py) da ramificação ovinogestApp
nesse repositório do git e substitua na pasta ovinogestApp:

![image](https://github.com/user-attachments/assets/4683e378-ff29-4192-a1b8-0ea0d53f2347)

Após isso, baixe os arquivos (adm_ovino , new_ovino , publico_ovino) da ramificação
templates nesse repositório do git e substitua na pasta dentro da pasta templates 
que se encontra dentro da pasta ovinogestApp:

![image](https://github.com/user-attachments/assets/46d7b01a-ffde-468f-927d-b123c55d95ea)

===================================================================================

# Instalação dos serviços Bootstrap

Acesse a página web: https://getbootstrap.com/docs/5.3/getting-started/download/
e baixe o css e o js

![image](https://github.com/user-attachments/assets/cb868a01-1978-4c82-a0ca-4fb9da6057a8)

Extraia a pasta:

![image](https://github.com/user-attachments/assets/a3e3d601-8571-4e17-91be-02a9d35b2651)

Por fim, copie as pastas "css" e "js" para a pasta static do projeto:

![image](https://github.com/user-attachments/assets/d7777c61-6f64-45ad-b594-0ff2980b8ced)

![image](https://github.com/user-attachments/assets/9a56ca9e-a3af-4dcd-bc80-99757598124f)

===================================================================================

# Criando um super usuário para o projeto

Retorne ao terminal e crie o super usuário:

> py manage.py createsuperuser

O terminal retornará as opções para nome, email e senha. Utilize as seguintes
credenciais:

> Username: dev
> Email address:
> Password: 12345678

===================================================================================
