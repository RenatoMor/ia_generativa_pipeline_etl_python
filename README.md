<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Geração de Notícias de Segurança Cibernética usando IA</span>
</h1>

Santander Dev Week - 2023

Este projeto é um exemplo de como utilizar tecnologias como Python, Pandas, Requests, OpenAI e APIs para extrair informações de um arquivo CSV, transformar esses dados com a ajuda da IA e, em seguida, carregar os resultados de volta em uma API.

## Pré-requisitos

Certifique-se de ter as seguintes bibliotecas e recursos instalados antes de executar o projeto:

```
pip install openai
pip install pandas
pip install requests
```

## Uso

```
import pandas as pd
import requests
import json
import openai
```
## Etapas do Projeto

### 1. Extração de Dados
Nesta etapa, o projeto começa lendo um arquivo CSV contendo dados de usuários. O código utiliza a biblioteca Pandas para carregar os dados e obter uma lista de IDs de usuário. Em seguida, ele faz chamadas à API do servidor sdw-2023 para obter detalhes dos usuários a partir dos IDs.

### 2. Transformação de Dados
Após a extração, o projeto utiliza a API do OpenAI para gerar notícias de segurança cibernética personalizadas para cada usuário. Para cada usuário, uma conversa é criada com a IA de modo a gerar uma mensagem relacionada à cibersegurança financeira. As notícias geradas são então anexadas aos dados do usuário.

### 3. Carregamento de Dados
Finalmente, o projeto faz atualizações nos perfis dos usuários, enviando as informações atualizadas de volta para a API sdw-2023. O status de atualização é verificado e exibido para cada usuário.

## Você pode me encontrar com os links abaixo

[![Gmail](https://img.shields.io/badge/-GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:renato.moreira@uni9.edu.br)
[![LinkedIn](https://img.shields.io/badge/-LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/renatomoreira-rm)


## Linguagens Utilizadas

![JavaScript](https://img.shields.io/badge/-JavaScript-000000?style=flat&logo=javascript)
![Python](https://img.shields.io/badge/-Python-000000?style=flat&logo=python)

## Tecnologias em Aprimoramento

![Git](https://img.shields.io/badge/-Git-222222?style=flat&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/-GitHub-222222?style=flat&logo=github&logoColor=181717)
![Linux](https://img.shields.io/badge/-Linux-222222?style=flat&logo=linux&logoColor=FCC624)
![Node.js](https://img.shields.io/badge/-Node.js-222222?style=flat&logo=node.js&logoColor=339933)
![Python](https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python)
![C#](https://img.shields.io/badge/C%23-000?style=for-the-badge&logo=c-sharp&logoColor=823085)

## IDE

[![Visual Studio Code](https://img.shields.io/badge/-VSCode-444444?style=flat&logo=visual-studio-code&logoColor=007ACC)](https://github.com/microsoft/vscode)

