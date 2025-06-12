# Config server

## O Config server é uma aplicação Spring Boot que fornece gerenciamento centralizado de configurações para sistemas distribuídos.

## Features
- Gerenciamento centralizado de configurações  
- Suporte a múltiplas fontes de configuração (Git, sistema de arquivos, etc.)  
- Suporte a atualizações dinâmicas de configuração  
- Integração com o Spring Boot Actuator para monitoramento e gerenciamento  
- Suporte ao Prometheus para coleta de métricas

## Getting Started

http://localhost:8888/spring-dynamic-consumer/dev

## Branches

- `main`: Utiliza do modo git com os arquivos de configurações em um repositório remoto.
- `config-local`: utiliza do modo nativo com os arquivos de configuração localizados no diretório `src/main/resources/config`  
