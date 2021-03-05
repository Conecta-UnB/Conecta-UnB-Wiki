# Backlog de time

## Histórico de versão

| Data | Versão | Descrição | Autor|
| - | - | - | - |
| 25/02/21 | 0.1 | Criação do documento, definição dos épicos, das features  e das histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 26/02/2021 | 0.2 | Adição da priorização nas histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 02/03/2021 | 0.3 | Adição dos tipos de usuários | Rhuan Marques, Júlio Schneider e Sara Campos |
| 05/03/2021 | 0.4 | Atualização do documento para o Safe essentials | Rhuan Marques, Júlio Schneider e Sara Campos |

## Features 

| ID | Descrição |
| - | - |
| F01 | Cadastrar usuário |
| F02 | Fazer login |
| F03 | Publicar notícias |
| F04 | Filtrar publicações |
| F05 | Visualizar notícias |
| F06 | Publicar eventos |
| F07 | Visualizar eventos |
| F08 | Visualizar mapa com fotos |
| F09 | Registrar EJ/EC/Lab |
| F10 | Visualizar dados da EJ/EC/Lab |
| F11 | Criar tópico de discussão no fórum |
| F12 | Visualizar tópicos de discussão |


## Critérios técnicos 

- Cobertura de testes unitários maior que 80%
- Lint

## Histórias de usuário 

| Feature | US | Critérios de aceitação | História de usuário |
| - | - | - | - |  
| F01 | US01 | - Criação da página do formulário de registro <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como visitante desejo realizar cadastro no site para poder ter acesso com privilégio |
| F01 | US02 | - Criação da página do formulário de registro <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como participante desejo solicitar acesso como gestor para criar publicações e/ou tópicos de fórum |
| F02 | US03 | - Criação da página de login <br> - Envio do formulário de login <br> - Autenticação dos dados de login |  Eu como administrador/gestor/participante desejo logar no meu perfil com o objetivo de realizar alguma ação que requer autenticação |
| F02 | US04 | - Criação da página de resgatar senha <br> - Envio do email de recuperação de senha do usuário <br> - Formulário de troca de senha | Eu como administrador/gestor/participante desejo resgatar minha senha  com o objetivo de fazer login |
| F03 | US05 | - Criação da página de formulário de publicação de notícias <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo criar uma notícia com o objetivo de publicar novas informações |
| F03 | US06 | - Recepção dos dados que devem ser excluídos | Eu como administrador/gestor desejo excluir uma notícia com o objetivo de remover a informação |
| F04 | US07 | - Registro das informações para filtragem das notícias no banco de dados | Eu como administrador/gestor desejo selecionar filtros (data, palavra-chave) para a publicação  com o objetivo de facilitar acesso para os usuários |
| F04 | US08 | - Busca das notícias no banco de dados baseado no filtro selecionado | Eu como visitante desejo filtrar as publicações com o intuito de visualizar publicações de caráter específico |
| F05 | US09 | - Criação da página de notícias <br> - Disponibilização de notícias relevantes (por tempo e popularidade) | Eu como visitante desejo visualizar notícias com o objetivo de me informar |
| F05 | US10 | - Criação da página de formulário de denúncia <br> - Envio do formulário de denúncia para o banco de dados <br> - Disponibilização da denúncia para o administrador | Eu como visitante desejo denunciar uma notícia com o objetivo de alertar os administradores sobre seu conteúdo |
| F06 | US11 | - Criação da página de formulário de publicação de eventos <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo publicar um evento com o objetivo de manter as pessoas a par de novos eventos |
| F06 | US12 | - Recepção dos dados que devem ser excluídos | Eu como administrador desejo excluir um evento com o objetivo de retirar da página |
| F06 | US13 | - Criação da página de formulário de alteração de dados <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser alterados | Eu como administrador/gestor desejo editar dados de um evento com o objetivo de manter a publicação atualizada |
| F07 | US14 | - Criação da página de eventos <br> - Disponibilização de eventos relevantes (por tempo e popularidade) <br> | Eu como visitante desejo visualizar um evento com o objetivo de acessar as informações sobre o mesmo |
| F08 | US15 | - Criação da página do mapa | Eu como visitante desejo visualizar o mapa da FGA com o objetivo de me localizar |
| F08 | US16 | - Criação da página de galeria de fotos <br> | Eu como visitante desejo acessar uma galeria de fotos da FGA com o objetivo de  conhecer  o espaço do campi |
| F09 | US17 | - Criação da página de formulário de registro de EJ/EC/Lab <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo registrar uma empresa júnior/equipe de competição/laboratório com o objetivo de expô-la no site |
| F09 | US18 | - Criação da página de formulário de alteração de dados <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser alterados | Eu como administrador/gestor desejo atualizar os dados de uma EJ/EC/Lab com o objetivo de manter o registro e informações atualizados | 
| F10 | US19 | - Criação da página da EJ/EC/Lab | Eu como visitante desejo ter acesso aos dados das EJs/ECs/Lab com o intuito de me informar sobre a equipe |
| F11 | US20 | - Criação do formulário do tópico de discussão <br> - Criação da página do tópico de discussão | Eu como administrador/gestor desejo criar um tópico de discussão com o objetivo de promover interação sobre um  assunto |
| F11 | US21 | - Recepção dos dados que devem ser excluídos | Eu como administrador desejo deletar um tópico de discussão com o objetivo de desfazer/encerrar o debate |
| F12 | US22 | - Criação da página de formulário de denúncia <br> - Envio do formulário de denúncia para o banco de dados <br> - Disponibilização da denúncia para o administrador | Eu como visitante desejo denunciar um tópico/comentário do fórum com o objetivo de solicitar revisão dos administradores |
| F12 | US23 | - Envio do comentário do usuário ao banco de dados <br> - Disponibilização do comentário do usuário | Eu como participante desejo comentar num tópico de discussão com o objetivo de interagir num debate |