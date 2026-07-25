# Department Network (Cisco Packet Tracer)
Projeto desenvolvido para a disciplina de **Redes de Computadores I** da **Universidade Estadual de Maringá (UEM)**.

O trabalho consiste no projeto e na implementação da infraestrutura de rede de um Departamento de Computação utilizando o Cisco Packet Tracer. Foram configuradas diferentes sub-redes, roteadores, switches e servidores, permitindo a comunicação entre os setores do departamento e a disponibilização de serviços de rede.

## Estrutura da Rede

A topologia é composta pelos seguintes setores:

- Laboratório 1;
- Laboratório 2;
- Secretaria;
- Sala dos Professores;
- Data Center.

Cada setor possui sua própria sub-rede IPv4 e é interligado por roteadores utilizando enlaces ponto a ponto.

## Funcionalidades Implementadas

- Planejamento do endereçamento IPv4;
- Configuração estática dos dispositivos;
- Roteamento estático entre sub-redes;
- Servidor HTTP;
- Servidor DNS;
- Servidor DHCP;
- DHCP Relay (`ip helper-address`);
- Testes de conectividade e validação dos serviços.

## Organização do Projeto

O desenvolvimento foi dividido em duas etapas:

### Parte 1 – Configuração Estática de Endereçamento IPv4

- Configuração manual dos endereços IPv4;
- Configuração dos gateways padrão;
- Configuração do servidor DNS;
- Configuração do servidor HTTP;
- Configuração do roteamento estático;
- Testes de conectividade entre as sub-redes.

### Parte 2 – Configuração Dinâmica de Endereçamento IPv4

- Configuração dos pools DHCP;
- Configuração do DHCP Relay nos roteadores;
- Obtenção automática de endereços IPv4 pelos dispositivos;
- Validação do funcionamento do DHCP.

## Tecnologias Utilizadas

- Cisco Packet Tracer
- IPv4
- Roteamento Estático
- DHCP
- DNS
- HTTP

## Arquivos

- `Relatorio_Redes_1.pdf` — relatório completo do projeto.
- `topologia_departamento_p1.pkt` — topologia da parte 1 desenvolvida no Cisco Packet Tracer.
- `topologia_departamento_p2.pkt` — topologia da parte 2 desenvolvida no Cisco Packet Tracer.

## Autores
- Gabriel Libardi Lulu
- Lucas de Oliveira Fratus

Universidade Estadual de Maringá (UEM)
Curso de Ciência da Computação
