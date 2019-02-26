# PROJETO DE ESTUDO SPRING CLOUD E SPRING BOOT

Projeto de estudo utilizado para criar uma Arquitetura de MicroServices com Spring Cloud e Spring Boot.

## Config Server

Neste projeto temos o Servidor de Configuração, que tem como objetivo de centralizar todas as configurações da nossa rede de Microservices em um só lugar.

Desta forma todos os arquivos de configuração dos nossos microserviços estarão em um repositório git e o Servidor de Configuração será o responsável por ler as informações no repositório e fornece-las às aplicações através de requests HTTP.
