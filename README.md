

A preparacao do ambiente consiste em:
1 - Identificar a maquina que vai disparar os comandos Ansible
2 - Identificar as maquinas alvo
3 - Configurar a comunicacao SSH entre a maquina Ansible e as maquinas alvo (usuario no grupo sudo, configurar para nao pedir senha)

Para este laboratorio vamos usar a arquitetura de rede criada no vagrant-lab.

<diagrama do laboratorio>

O que e o ansible?
Pre requisitos
# para voce
SO - A maquina Ansible devera ser uma maquina Linux ou Mac OS.
Python - versao > 3

# para seu computador
SO - qualquer Sistema Operacional 
Python - Python instalado na maquina Ansible e nas maquinas alvo

# Conhecimento Basico
    #ad-hoc
    #playbook
    #tasks
    #modules
        ip
        yum
        apt
        shell
        unarchive
        file
    #vars
    #handlers
    #registers
    #facts

# Fazendo a diferenca
    #Roles

# Laboratorios
    #Laboratorio 01
    #Laboratorio 02
    #Laboratorio 03