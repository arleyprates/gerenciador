gerenciador
===========

Gerenciar vendas de produtos executando em uma Virtual Machine

Utilizando Virtualbox para virtualização de uma infraestrutura com sistema operacional CentOS-6.5-i386

Packages additional:

``vim``
``git``
``samba``
``php``
``mysql``

Primeiro passo é instalar o Virtualbox. 

``https://www.virtualbox.org/wiki/Downloads``

Pelo Virtualbox é preciso importar a Máquina Virtual CentOS

Start a VM

Entre com user e password

Verifique o endereço IP da interface eth0 na VM

Na sua máquina edite o arquivo hosts mapeando o endereco IP para nome de um domínio

``172.168.0.10 gerenciador.dev``

Entre no broswer e digite o nome do domínio

``http://gerenciador.dev``
