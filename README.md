# Simulação de Rede Básica

## Descrição do Projeto

Este projeto consiste em uma simulação básica de rede, utilizando o Cisco Packet Tracer, com o objetivo de demonstrar a comunicação entre dispositivos finais, switches e roteadores.
(https://github.com/CassioFreires/basic-network-simulation/blob/main/rede.png)

## Topologia da Rede em árvore

A topologia da rede é composta pelos seguintes elementos:

- 1 Roteador
- 2 Switches
- 5 Dispositivos Finais (PCs, laptops, etc.)
- 1 Servidor do Google

A comunicação ocorre da seguinte forma:

- Os dispositivos finais estão conectados a um switch.
- O switch está conectado a um roteador.
- O roteador encaminha os dados para outra rede de destino.
- Um segundo switch está conectado a um servidor do Google.

## Configuração da Rede

### Dispositivos Finais

1. PC_1: IP 192.168.0.2, Máscara de Sub-rede 255.255.255.0, Getwey Default 192.168.0.1
2. PC_2: IP 192.168.0.3, Máscara de Sub-rede 255.255.255.0, Getwey Default 192.168.0.1
3. PC_3: IP 192.168.0.4, Máscara de Sub-rede 255.255.255.0, Getwey Default 192.168.0.1
4. PC_4: IP 192.168.0.5, Máscara de Sub-rede 255.255.255.0, Getwey Default 192.168.0.1
5. PC_5: IP 192.168.0.6, Máscara de Sub-rede 255.255.255.0, Getwey Default 192.168.0.1

### Servidor do Google

6. SERVIDOR_GOOGLE: IP 8.1.1.1, Máscara de Sub-rede 255.0.0.0, Getwey Default 8.8.8.1

###  Switches
1. Switch_1: Rede dos dispositivos finais
2. Switch_2: Rede do servidor
 
### Roteador
1. Roteador_1: IP 192.168.0.1

## Como Executar a Simulação

1. Clone este repositório em sua máquina local.
2. Abra o arquivo do projeto no Cisco Packet Tracer.
3. Inicie a simulação.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, correções ou novas funcionalidades.

## Contato

- nome: Cassio souza
- Email: cassio_souza@live.com
- Linkedin: !LinkedIn(https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=LinkedIn&logoColor=white)]([https://www.linkedin.com/in/seu_nome_no_linkedin/](https://www.linkedin.com/in/cassio-souza-08347a157/)

Developer by cassio souza 2024.
