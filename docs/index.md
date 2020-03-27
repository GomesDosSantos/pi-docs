# Projeto Integrador ADS Fatec

[![License: CC BY 4.0](https://img.shields.io/badge/license-MIT-green)](https://github.com/ProjetoIntegradorADSFatec/projeto-integrador-ads-fatec/blob/master/LICENSE)

Projeto Integrador ADS Fatec - São José dos Campos proposto pela empresa [Visiona](http://www.visionaespacial.com.br/) para a identificação de talhões (unidade mínima de cultivo de uma propriedade com características em comum). Link Oficial para o projeto [Github](https://github.com/ProjetoIntegradorADSFatec).

## Integrantes do Grupo:

- Abner Ernâni dos Anjos (Scrum Master - SM)
- Joâo de Freitas (Project Owner - PO)
- Guilherme Gomes (Back end Developer - DEV)
- João Arruda (Front end Developer - DEV)
- Tábata Glória (Front end Developer - DEV)

## Solução:

Desenvolver um Sistema Web Gis - Sistema de informação Geográfico - com uma interface gráfica agradável ao usuário e de fácil utilização e intuitiva, com uma área de visualização de imagens do mapa, conforme a região e o período de tempo selecionados pelo usuário, permitindo a manipulação da imagem (aumentar ou diminuir e demarcação) e permitir o download desse arquivo para armazenamento.


## Implementação:

Como implementar? Tecnologias. Plataformas. Ferramentas.

Para a implementação será necessário a utilização das seguintes tecnologias:

### Landsat-8 API
Satélite de satélite de observação da Terra, esses dados das imagens  podem ser usados facilmente com qualquer software que reconheça arquivos GeoTIFF através de um arquivo CSV de índice dos dados do Landsat.

### Sentinel-2 API
É uma constelação de dois satélites de observação da Terra SEUS Os dados são ideais para aplicativos de agricultura, silvicultura e outros tipos de administração de terra. esse conjunto de dados está disponível gratuitamente no programa Google Public Cloud Data.

### Geo Server
É um servidor de código aberto escrito em Java que permite aos usuários compartilhar, processar e editar dados geoespaciais. Projetado para interoperabilidade, publica dados de qualquer fonte de dados espaciais importantes usando padrões abertos.

### PostgreSQL
É um sistema de gerenciamento de banco de dados objeto-relacional (SGBDOR) baseado no POSTGRES Versão 4.2.

### Spring Boot
Projeto da Spring que veio para facilitar o processo de configuração e publicação de aplicações. Pode-se escolher os módulos que precisa através dos starters que inclui no pom.xml do projeto. Basicamente, são dependências que agrupam outras dependências.

### Angular
É uma estrutura de design de aplicativo e plataforma de desenvolvimento para criar aplicativos de página única eficientes e sofisticados.

### Java
É uma linguagem de programação orientada a objetos que é amplamente usada para o desenvolvimento de sites e aplicativos. Permite o desenvolvimento de programas multiplataforma, que podem ser executados em qualquer dispositivo.

### Python
É uma linguagem de programação de alto nível, interpretada, de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte, para a implementação da inteligencia artificial.

### Git Hub
Sistema de controle de versão distribuido e gerenciamento de código-fonte, fornece controle de acesso e vários recursos de colaboração, como rastreamento de erros, solicitações de recursos, gerenciamento de tarefas e wikis para cada projeto.

### Microsoft TEAM
Trata-se de um aplicativo de bate-papo em grupo que permite o gerenciamento de diversas conversas em um único ambiente de controle. Foi desenvolvido para facilitar a comunicação e promover a colaboração entre as equipes da empresa/projeto.

## Componentes:

- [Sistema Inteligente](https://github.com/ProjetoIntegradorADSFatec) - construção da base de dados a ser consumida;
- [API](https://github.com/ProjetoIntegradorADSFatec/api-restful) - intermédio para a base de dados e o sistema Web GIS;
- [Sistema Web GIS](https://github.com/ProjetoIntegradorADSFatec/web-gis) - visualização do resultado final;