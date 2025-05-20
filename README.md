<span id="topo">
<h1 align='center'>
:boar: EQUIPE JAVALI :boar:

APRENDIZAGEM POR PROJETOS INTEGRADOS

5º SEMESTRE DSM - 2025-1
</h1>

<h1 align='center'> :keyboard:  :keyboard: </h1>

## :mag_right: Índice
<p align='center'>
    <a href="#objetivo">Objetivo</a> | 
    <a href="#sprints">Sprints</a> |
    <a href="#backlog">Backlog total</a> |
    <a href="#tecnologias">Tecnologias</a> |
    <a href="#arquitetura">Arquitetura</a> |
    <a href="#instrucoes">Instruções para Executar o Projeto</a> |
    <a href="#equipe">Equipe</a> 
</p>

<span id='objetivo'>

## :dart: Objetivo
<p align='justify'>
O objetivo do projeto é desenvolver uma plataforma que possibilite a criação e gerenciamento de agentes de Inteligência Artificial focados em atendimento interno. Esses agentes serão personalizados para responder questionamentos específicos, enquanto um sistema de permissões garante que cada usuário só tenha acesso aos agentes autorizados. Além disso, o projeto envolve a integração com um banco de dados na nuvem para armazenar o histórico de interações e a criação de um aplicativo móvel que facilite a comunicação via chat, entregando respostas rápidas e precisas às dúvidas dos usuários.
</p>

<span id='sprints'>

## :pushpin: Sprints
Na tabela abaixo é possível visualizar os resultados de cada Sprint. 
| Sprint |   Início    |    Entrega  |               Status                     |                    Relatório                    |
|:------:|:-----------:|:-----------:|:----------------------------------------------:|:-----------------------------------------------:|
|   01   | 10/03/2025  | 30/03/2025  | :white_check_mark: Concluído        | [Clique aqui](https://github.com/equipe-javali/API_5/tree/sprint1) |
|   02   | 07/04/2025  | 27/04/2025  | :white_check_mark: Concluído                          | [Clique aqui](https://github.com/equipe-javali/API_5/tree/sprint2)  |
|   03   | 05/05/2025  | 25/05/2025  | :soon: Não iniciada                           | [Clique aqui](https://github.com/equipe-javali/API_5/tree/sprint3)  |

→ [Voltar ao topo](#topo)

<span id='backlog'>

## :clipboard: Requisitos Funcionais
:pushpin: RF-1 Cadastro de Agentes de IA Personalizados: Permitir o cadastro de agentes de IA com conteúdos personalizados (ex.: um agente para responder dúvidas sobre um sistema de RH, outro para um ERP, etc.)

:pushpin: RF-2 Interação com Agentes de IA via Chat: Implementar um sistema de chat, onde os usuários possam interagir com os agentes para
esclarecer dúvidas.

:pushpin: RF-3 Controle de Acesso a Agentes de IA: Criar um sistema de permissões, onde o administrador possa definir quais agentes cada
usuário pode acessar.

:pushpin: RF-4 Armazenamento do Histórico de Interações com Agentes de IA: Armazenar o histórico de interações entre usuários e agentes em um banco de dados na
nuvem.

:pushpin: RF-5 Dashboard Administrativo para Gerenciamento de Agentes e Estatísticas: Desenvolver um dashboard administrativo para gerenciar os agentes, permissões e
visualizar estatísticas de uso.


→ [Voltar ao topo](#topo)

## :clipboard: Requisitos Não Funcionais
:pushpin: RNF-1 Desenvolvimento do Aplicativo Móvel: Utilizar ReactNative ou Flutter para o desenvolvimento do aplicativo móvel.

:pushpin: RNF-2 Persistência de Dados no Banco de Dados: Implementar a persistência de dados em um banco de dados compatível (MySQL,
MongoDB, Oracle, etc.).

:pushpin: RNF-3 Otimização do Tempo de Resposta nas Interações com Agentes de IA: Assegurar um tempo de resposta adequado para as interações no chat.

:pushpin: RNF-4 Documentação da API: Criar uma documentação técnica com instruções de instalação, uso e estrutura da API.

##  Épicos

![Epics](https://github.com/user-attachments/assets/feb1fcf2-31d7-4492-9fbf-d52c01be1c54)

## Backlog total
![Backlog Total 1](https://github.com/user-attachments/assets/f187c6b7-1053-4934-b18f-60218648b7ad)
![Backlog Total 2](https://github.com/user-attachments/assets/ce86f043-1b4f-4182-a3e3-a24a94ec29f2)
![Backlog Total 3](https://github.com/user-attachments/assets/d925d6b8-a183-41e9-b355-5664b3169e26)

→ [Voltar ao topo](#topo)

<span id='tecnologias'>

## 💻 Tecnologias
Foram usadas as seguintes ferramentas, linguagens e tecnologias para a execução do projeto:
- [Figma](https://www.figma.com): Prototipagem
- [Git](https://git-scm.com): Versionamento
- [GitHub](https://github.com/): Armazenamento de código e documentação
- [Python](https://www.python.org/): Linguagem de programação do back-end
- [Shortcut](https://tree.taiga.io): Organização de tarefas
- [ReactNative](https://pt-br.reactjs.org/): Framework do front-end mobile
- [Swagger](https://swagger.io): Documentação das rotas no back-end

→ [Voltar ao topo](#topo)

<span id="arquitetura">
    
## Arquitetura do sistema

![API 5DSM - Arquitetura](https://github.com/user-attachments/assets/3ab97b7f-eb75-4c32-808a-68e4e7c27fad)

→ [Voltar ao topo](#topo)

<span id="instrucoes">

## :gear: Instruções para Executar o Projeto

### Banco de Dados

1. Instalar o PostgreSQL: [Download PostgreSQL](https://www.postgresql.org/download/)
   (Selecionar as Command line tools nas opções de instalação)
2. Criar um banco de dados vazio: `create database omni_BD;`

### Backend 

1. Para rodar a aplicação, é necessário instalar o Python: [Download Python](https://www.python.org/downloads/)
2. Para clonar o repositório do backend, digite no prompt de comando: ```git clone https://github.com/equipe-javali/API_5_BACK```
3. Para entrar no repositório do backend, digite no prompt de comando: ```cd API_5_BACK```
4. Para criar o ambiente virtual, digite no prompt de comando: ```py -m venv env```
5. Para ativar o ambiente virtual, digite no prompt de comando: ```env\Scripts\activate```
6. Para instalar os requisitos do sistema, digite no prompt de comando: ```pip install -r requirements.txt```
7. Para configurar as variáveis do database, abra o arquivo: ```api\settings.py``` e configure DATABASES: 
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',  # Use PostgreSQL
        'NAME': 'omni_BD',                          # Nome do database do banco
        'USER': 'root',                             # Nome do usuário do banco
        'PASSWORD': 'root',                         # Senha do usuário do banco
        'HOST': 'localhost',                        # Host do banco
        'PORT': '5432',                             # Port do banco
        'OPTIONS': {
            'sslmode': 'require',                   # Modo do SSL
        }
    }
}
```
8. Para executar a aplicação, digite no prompt de comando: ```python manage.py runserver```
> OBS: Caso queira executar a aplicação no emulador, digite no prompt de comando: ```python manage.py runserver 0.0.0.0:8000```

### Frontend
1. Para clonar o repositório do frontend, digite no prompt de comando: `git clone https://github.com/equipe-javali/API_5_FRONT`
> OBS: A aplicação deverá ser clonada na raiz do sistema. Exemplo: C:\
2. Para entrar no repositório do backend, digite no prompt de comando: ```cd API_5_FRONT\API_5```
3. Para instalar os requisitos do sistema, digite no prompt de comando: ```npm install```
4. Para executar a aplicação, digite no prompt de comando: ```npm start```
> OBS: O backend deverá estar rodando para a aplicação funcionar.

→ [Voltar ao topo](#topo)

<span id="equipe">

## :busts_in_silhouette: Equipe
|     Função    |         Nome        |                                                                                                    LinkedIn                                                                                                                             |                                                                                    GitHub                                                                                    |
| :-----------: | :-----------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner      | Bruno Serpa         | <a href="https://www.linkedin.com/in/brunoserpa" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                                        | <a href="https://github.com/BrunoSerpa" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>           |
| Scrum Master      | Marcus Betti        | <a href="https://www.linkedin.com/in/marcus-betti-715b6614a/" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                           | <a href="https://github.com/marcusvbe"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>                            |
| Dev Team | Mariana Izumi       | <a href="https://www.linkedin.com/in/mariana-izumi-developer" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                           | <a href="https://github.com/MariMiks/" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>            |
| Dev Team  | Rafael Nunes        | <a href="https://www.linkedin.com/in/rafael-nunes-silva" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                                | <a href="https://github.com/Rafael-Nunes-Silva" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |
| Dev Team      | Katiane Soares      | <a href="https://www.linkedin.com/in/katiane-soares-4b8193245/" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                         | <a href="https://github.com/Katianefatec" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>         |
| Dev Team      | Maria Gabriela      | <a href="https://www.linkedin.com/in/gabrieia-mello-3819a9270/" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">                         | <a href="https://github.com/MariaGabrielaMello" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |
| Dev Team      | Silmara Bittencourt | <a href="https://www.linkedin.com/in/silmara-in%C3%AAs-bittencourt-da-costa-243478214/" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> | <a href="https://github.com/SBittencourt"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>                         |

→ [Voltar ao topo](#topo)
