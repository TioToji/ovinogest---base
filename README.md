# ovinogest---base

Repositorio da base do projeto Ovinogest

Esses são apenas os arquivos base do projeto (apenas para substituir os antigos no seu projeto), para rodar o servidor e verificar a funcionalidade você precisa ter o projeto em um ambiente virtual e obviamente ter o projeto tbm já pré intalado. 

# Processo de criação do Projeto

Segue os comandos via terminal para a criação do ambiente virtual e do projeto:

==================================================================================

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

==================================================================================

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

==================================================================================

# Configurações do Django

Ja com os pacotes instalados, vamos para as configurações:

------ Startar o projeto ------

> django-admin startproject ovinogest

------ Startar o App da aplicação ------

> python manage.py startapp ovinogestApp

==================================================================================

# Substituição dos arquivos

Após seguir esses passos, baixe os arquivos (settings.py e urls.py) da ramificação 
ovinogest nesse repositório do git e substitua na pasta ovinogest:

![image](https://github.com/user-attachments/assets/7067fdeb-232f-434f-a4c2-2025d6303345)

Também baixe os arquivos (forms.py , models.py  e views.py) da ramificação ovinogestApp
nesse repositório do git e substitua na pasta ovinogestApp:

![image](https://github.com/user-attachments/assets/4683e378-ff29-4192-a1b8-0ea0d53f2347)

==================================================================================


