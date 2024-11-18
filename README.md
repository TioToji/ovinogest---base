# ovinogest---base

Repositorio da base do projeto Ovinogest

Esses são apenas os arquivos base do projeto (apenas para substituir os antigos no seu projeto), para rodar o servidor e verificar a funcionalidade você precisa ter o projeto em um ambiente virtual e obviamente ter o projeto tbm já pré intalado. Segue os comandos via terminal para a criação do ambiente virtual e do projeto:

==================================================================================

Primeiro, precisa criar uma pasta:

> mkdir ovinogest
> cd ovinogest

==================================================================================

Partindo para a criação do ambiente virtual:

> py -m venv myenv

Caso não dê certo, tente:

> python -m venv myenv

ou

> python3 -m venv myenv

Pronto, seu ambiente virtual foi criado!!

==================================================================================

Agora precisa entrar nesse ambiente virtual:

> myenv\Scripts\activate

Se der certo, o status do seu terminal deve ficar parecido com isso:

> (myenv) C:\ovinogest>

==================================================================================

Ja dentro do ambiente, precisa instalar alguns pacotes nele para conseguir rodar o
projeto no estado atual:

> pip install requests  #Instalar todos os pacotes python necessários
