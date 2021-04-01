# Backlog de time

## Histórico de versão

| Data | Versão | Descrição | Autor|
| - | - | - | - |
| 25/02/21 | 0.1 | Criação do documento, definição dos épicos, das features  e das histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 26/02/2021 | 0.2 | Adição da priorização nas histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 02/03/2021 | 0.3 | Adição dos tipos de usuários | Rhuan Marques, Júlio Schneider e Sara Campos |
| 05/03/2021 | 0.4 | Atualização do documento para o Safe essentials | Rhuan Marques, Júlio Schneider e Sara Campos |
| 18/03/2021 | 0.5 | Adição de épicos e conversão em um único documento | João Vitor Lopes, Júlio Schneider e Sara Campos |
| 28/03/2021 | 0.6 | Adicionando tabela de requisitos não funcionais | Sara Campos, Júlio Schneider, João Lopes, Rhuan Marques e Edvan Gomes | 
| 30/03/2021 | 0.7 | Adicionando priorização e redefinindo critérios de aceitação | Sara Campos, Júlio Schneider, João Lopes e Rhuan Marques |

## Tema

Gerenciamento e armazenamento de informações relacionadas ao campi da Faculdade do Gama.

## Épicos

| Número | Épico |
|--------|-------|
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | Gerenciamento de usuários |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | Gerenciamento de publicações |
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | Apresentação de recursos do campus FGA |
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | Gerenciamento de fóruns |

## Features 

| Épico | Número | Feature |
| - | - | - | 
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | Cadastrar usuário |
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | Fazer login  | 
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | Publicar notícias | 
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | Filtrar publicações (notícias e eventos) | 
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | Visualizar notícias | 
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | Publicar eventos | 
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/14) | Visualizar eventos | 
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | Visualizar mapa com fotos | 
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | Registrar EJ/EC/Lab | 
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/9) | Visualizar dados da EJ/EC/Lab | 
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | Criar tópico de discussão no fórum | 
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | Visualizar tópicos de discussão | 


## Critérios técnicos das histórias de usuário

- Cobertura de testes unitários maior que 80%
- Lint

## Histórias de usuário 

| Feature | US | Critérios de aceitação | História de usuário | Prioridade |
| - | - | - | - | - |
| [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | [US01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/23) | - O usuário deve poder enviar matrícula, nome, e-mail, telefone e senha ao sistema <br> - O usuário deve ser informado se o cadastro foi realizado com sucesso <br> | Eu como visitante desejo realizar cadastro no site para poder ter acesso com privilégio | must have |
| [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | [US02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/26) | - O usuário participante deve poder enviar uma solicitação de acesso com privilégio de gestor <br> - O usuário gestor deve poder aceitar uma solicitação de acesso com privilégio | Eu como participante desejo solicitar acesso como gestor para criar publicações e/ou tópicos de fórum | should have |
| [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | [US03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/29) | - O usuário deve poder informar e-mail e senha <br> - O usuário deve poder acessar o sistema estando conectado |  Eu como administrador/gestor/participante desejo logar no meu perfil com o objetivo de realizar alguma ação que requer autenticação | must have |
| [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | [US04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/33) | - O usuário deve poder solicitar recuperação de senha <br> - O usuário deve receber um e-mail com as instruções pra redefinir senha <br> - O usuário deve poder indicar a nova senha | Eu como administrador/gestor/participante desejo resgatar minha senha  com o objetivo de fazer login | could have |
| [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | [US05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/36) | - O usuário deve ter acesso a um formulário de criação de notícia <br> - O usuário deve preencher os campos de título, conteúdo, autor e imagem (opcional) <br> - O usuário deve poder enviar o formulário | Eu como administrador/gestor desejo criar uma notícia com o objetivo de publicar novas informações | must have |
| [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | [US06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/38) | - O usuário deve poder selecionar a notícia a ser excluída <br> - O usuário deve poder apagar a notícia | Eu como administrador desejo excluir uma notícia com o objetivo de remover a informação | should have |
| [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | [US07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/39) | - O usuário deve poder colocar tag para filtragem | Eu como administrador/gestor desejo selecionar filtros (data, palavra-chave) para a publicação  com o objetivo de facilitar acesso para os usuários | could have |
| [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | [US08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/40) | - O usuário deve poder selecionar filtro (tag ou texto) para buscar notícias e eventos <br> - O usuário deve poder visualizar as notícias e eventos relacionadas ao filtro | Eu como visitante desejo filtrar as publicações com o intuito de visualizar publicações de caráter específico | could have |
| [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | [US09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/41) | - O usuário deve poder acessar uma página com as notícias <br> - O usuário deve poder acessar uma notícia específica selecionada | Eu como visitante desejo visualizar notícias com o objetivo de me informar | must have |
| [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | [US10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/42) | - O usuário deve poder enviar um formulário de denúncia ao sistema | Eu como visitante desejo denunciar uma notícia com o objetivo de alertar os administradores sobre seu conteúdo | should have |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/37) | - O usuário deve ter acesso a um formulário de criação de evento <br> - O usuário deve preencher os campos de título, descrição, organizador e imagem (opcional) <br> - O usuário deve poder enviar o formulário  | Eu como administrador/gestor desejo publicar um evento com o objetivo de manter as pessoas a par de novos eventos |  must have |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/35) | - O usuário deve poder selecionar o evento a ser excluída <br> - O usuário deve poder apagar o evento | Eu como administrador/gestor desejo excluir um evento com o objetivo de retirar da página | could have |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US13](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/34) | - O usuário deve poder ter acesso a um formulário para editar qualquer um dos dados <br> - O usuário deve poder enviar os dados atualizados ao sistema | Eu como administrador/gestor desejo editar dados de um evento com o objetivo de manter a publicação atualizada | should have |
| [F07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/14) | [US14](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/32) | - O usuário deve poder acessar uma página com os eventos <br> - O usuário deve poder acessar um evento específico selecionado | Eu como visitante desejo visualizar um evento com o objetivo de acessar as informações sobre o mesmo | must have |
| [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | [US15](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/31) | - O usuário deve poder acessar o mapa <br> - O usuário deve poder visualizar locais do campi | Eu como visitante desejo visualizar o mapa da FGA com o objetivo de me localizar | could have |
| [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | [US16](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/30) | - O usuário deve poder ter acesso as fotos <br> - O usuário deve poder visualizar as fotos | Eu como visitante desejo acessar uma galeria de fotos da FGA com o objetivo de  conhecer  o espaço do campi | could have |
| [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | [US17](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/28) | - O usuário deve ter acesso a um formulário de registro de EJ/EC/Lab <br> - O usuário deve preencher os campos de nome, descrição, e-mail, telefone, facebook, instagram, site e foto (opcional) <br> - O usuário deve poder enviar o formulário | Eu como administrador/gestor desejo registrar uma empresa júnior/equipe de competição/laboratório com o objetivo de expô-la no site |  must have |
| [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | [US18](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/27) | - O usuário deve poder ter acesso a um formulário para editar qualquer um dos dados <br> - O usuário deve poder enviar os dados atualizados ao sistema | Eu como administrador/gestor desejo atualizar os dados de uma EJ/EC/Lab com o objetivo de manter o registro e informações atualizados | must have |
| [F10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/9) | [US19](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/25) | - O usuário deve poder acessar uma página com as EJs/ECs/Labs <br> - O usuário deve poder acessar uma EJ/EC/Lab específica selecionada  | Eu como visitante desejo ter acesso aos dados das EJs/ECs/Lab com o intuito de me informar sobre a equipe | must have |
| [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | [US20](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/24) | - O usuário deve ter acesso a um formulário de criação de tópico de discussão <br> - O usuário deve preencher os campos de título e descrição <br> - O usuário deve poder enviar o formulário | Eu como administrador/gestor desejo criar um tópico de discussão com o objetivo de promover interação sobre um  assunto | must have |
| [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | [US21](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/22) | - O usuário deve poder selecionar o tópico de discussão a ser excluído <br> - O usuário deve poder apagar o tópico de discussão  | Eu como administrador desejo deletar um tópico de discussão com o objetivo de desfazer/encerrar o debate | should have |
| [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | [US22](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/21) | - O usuário deve poder enviar um formulário de denúncia ao sistema | Eu como visitante desejo denunciar um tópico/comentário do fórum com o objetivo de solicitar revisão dos administradores | should have |
| [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | [US23](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/19) | - O usuário deve ter acesso a um formulário de criação de tópico de discussão <br> - O usuário deve preencher o campo de descrição <br> - O usuário deve poder enviar o formulário | Eu como participante desejo comentar num tópico de discussão com o objetivo de interagir num debate | must have |

## Prioridade
| | | 
| - | - |
| Must Have | Tenho que fazer |
| Should Have | Devo fazer |
| Could Have | Poderia fazer | 
| Won’t Have | Não vou fazer |


## Requisitos não funcionais

| Identificador | Requisitos |
| - | - |
| RNF01 | Criação do git | 
| RNF02 | Ambiente de desenvolvimento backend |
| RNF03 | Ambiente de desenvolvimento frontend |
| RNF04 | Criação do banco de dados |
| RNF05 |  Criação de template para forms no front |
| RNF06 | Hospedagem do site |
| RNF07 | Validação de formulários | 
| RNF08 | Segurança de dados de usuário |
| RNF09 | Autenticação de usuários |