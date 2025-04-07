# API ADS 6º Semestre

# Projeto Plataforma de Treinamento de IA

<p align="center">
      <img src="/Documentacao/img/fullstack.png" alt="Logo da Equipe FullStack">

<span id="topo">
<p align="center">
    <a href="#sobre">Sobre</a>  | 
    <a href="#sprints">Entrega das Sprints</a>  |  
    <a href="#backlogs">Backlog do Produto</a>  |  
    <a href="#tecnologias">Tecnologias</a>  |  
    <a href="#commit">Padrão de Commit</a>  |
    <a href="#branch">Estratégia de Branch</a>  |
    <a href="#equipe">Equipe</a>  |  
    <a href="#focal">Focal Point</a>  
    
</p>
   
<span id="sobre">

## :bookmark_tabs: Sobre o projeto

**Problema:** 
Com o crescimento do uso de Modelos de Linguagem (LLMs) em diversas aplicações, surge a necessidade de aprimorar sua qualidade e precisão de forma contínua. No entanto, muitas abordagens de treinamento ainda carecem de envolvimento humano direto no processo de avaliação e melhoria. A ausência de uma plataforma centralizada que permita comparar, avaliar e fornecer feedback humano estruturado sobre as respostas dos LLMs dificulta o avanço de modelos mais alinhados às expectativas humanas em critérios como coerência, veracidade, naturalidade da linguagem e segurança.

**Proposta de Solução:** 
Para resolver esse desafio, será desenvolvida uma Plataforma de Treinamento de IA — uma solução web que permite ao usuário comparar respostas geradas por diferentes LLMs, avaliar as respostas com base em critérios definidos e fornecer feedback direto para o treinamento dos modelos utilizando técnica de Aprendizado por Reforço com Feedback Humano (RLHF).

A aplicação será construída com tecnologias modernas, como Vue.js no frontend, Python com FastAPI e Langchain no backend, utilizando MongoDB como banco de dados. A plataforma também contará com integração com bancos vetorizados como Pinecone ou Weaviate, garantindo eficiência na recuperação de informações.

Os usuários poderão enviar perguntas, visualizar respostas geradas por dois LLMs (OpenAI e Gemini), realizar avaliações detalhadas com base em critérios específicos, e contribuir ativamente para o aprimoramento dos modelos. A interface será desenvolvida com foco em usabilidade e acessibilidade, utilizando o Figma para validação rápida e iterativa de protótipos antes da implementação.


> _Projeto conduzido de acordo com a metodologia ágil SCRUM, que garante uma abordagem flexível e colaborativa, com entregas contínuas e foco na adaptação às necessidades dos usuários. Cada Sprint permitirá que funcionalidades como envio de prompts, exibição de respostas, avaliação com critérios, desempate entre respostas e integração com RAG (Retrieval-Augmented Generation) sejam implementadas e melhoradas progressivamente._

:pushpin: Status do Projeto: **Em desenvolvimento** 🚧



<br>

<span id="sprints">

### :spiral_calendar: Entrega das Sprints

| Sprint | Previsão de entrega | Status | Histórico |
|:--:|:----------:|:-------------------|:-------------------------------------------------:|
| 01 | 30/03/2025 | :white_check_mark: Concluído | [Ver relatório](https://github.com/FATEC-FULLSTACK/API6/blob/main/Documentacao/Sprint01/README.md) |
| 02 | 27/04/2025 | :construction: Em Desenvolvimento | [Ver relatório](https://github.com/FATEC-FULLSTACK/API6/blob/main/Documentacao/Sprint02/README.md) |
| 03 | 25/05/2025 | :construction: Em Desenvolvimento | [Ver relatório](https://github.com/FATEC-FULLSTACK/API6/blob/main/Documentacao/Sprint03/README.md) |


<br>


<span id="backlogs">

## :dart: Backlog do Produto

<p align="center">
      <img src="/Documentacao/img/backlog.png" alt="Backlog do Produto">


<br>


<span id="tecnologias">

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

<table>
  <thead>
    <th><img
    src="https://user-images.githubusercontent.com/89823203/190877360-8c7f93cf-5f62-4f49-8641-3b605deb513e.png"
    alt="Logo Figma"
    title="Figma"
    style="display: inline-block; margin: 0 auto; width: 60px"></th>
    <th><img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg"
    alt="Logo MongoDB"
    title="MongoDB"
    style="display: inline-block; margin: 0 auto; width: 70px"></th>
    <th><img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"
    alt="Logo Python"
    title="Python"
    style="display: inline-block; margin: 0 auto; width: 50px"></th>
    <th><img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg"
    alt="Logo Vue.js"
    title="Vue.js"
    style="display: inline-block; margin: 0 auto; width: 60px"></th>
    <th><img
    src="/docs/langchain.png"
    alt="Logo LangChain"
    title="LangChain"
    style="display: inline-block; margin: 0 auto; width: 60px"></th>
    <th><img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg"
    alt="Logo FastAPI"
    title="FastAPI"
    style="display: inline-block; margin: 0 auto; width: 60px"></th>
  </thead>

  <tbody>
    <td>Figma</td>
    <td>MongoDB</td>
    <td>Python</td>
    <td>Vue.js</td>
    <td>LangChain</td>
    <td>FastAPI</td>
  </tbody>

</table>


<br>


<span id="commit">

## :pencil: Padrão de Commits

Este projeto segue o padrão de commit descrito no link abaixo, garantindo clareza e organização no versionamento do código:

[Link Padrão de Commits](https://github.com/FATEC-FULLSTACK/API6/blob/main/Documentacao/Commits/README.md)


<br>


<span id="branch">

## :deciduous_tree:  Estratégia de Branch do Projeto

Este projeto adota um fluxo de trabalho baseado no Git Flow, com branches estruturadas para garantir organização e rastreabilidade durante o desenvolvimento. Abaixo está o link das diretrizes principais:

[Link Estratégia de Branch](https://github.com/FATEC-FULLSTACK/API6/blob/main/Documentacao/Branch/README.md)


<br>


<span id="equipe">

## :bust_in_silhouette: Equipe

|    Função     | Nome                             |                                                                                                                                                  LinkedIn & GitHub                                                                                                                                                   |
| :-----------: | :------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | Pedro Henrique Siqueira Cardoso        | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-cardoso-6b93011b6/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PhscZ) |
| Scrum Master  | Claudia de Carlos Braga Secco    |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/cláudia-braga-79b6b2278/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/ClaudiaCBS)   |
|   Dev Team    | Carlos Henrique Benício Costa                |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-henrique-b-40a4b5108/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Carlos-Henrique39)         |
|   Dev Team    | Giovani Carvalho Avila                |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/giovani-carvalho-avila-80593a224/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GiovaniAvila)         |
|   Dev Team    | Juliano Vitor Prado                |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/juliano-prado-078a3920b/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/julianopradoo)         |
|   Dev Team    | Leonardo Gazola Medeiros                |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/leonardo-gazola/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Leonardo-Gazola-Medeiros)         |
|   Dev Team    | Lucas Nunes Duarte do Nascimento |    [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-nunes-nascimento/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Lkduarte)     |
|   Dev Team    | Mateus de Sousa Raimundo         |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mateus-sousa-ba976423a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/MateusdiSousa)  |
|   Dev Team    | Thiago Carvalho da Silva         |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-silva-49bb74168/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/tsilvadev89)  |


<br>


<span id="focal">

## 🚀 Focal Point<a id="focal"></a>

|                                  PO²                                  |                                           M²                                           |
| :-------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
| <a href='https://www.linkedin.com/in/walmir-duque/'>Prof. José Walmir Gonçalves Duque</a> | <a href='http://lattes.cnpq.br/5948825528321491'>Prof. Eduardo Sakaue</a> |

→ [Voltar ao topo](#topo)