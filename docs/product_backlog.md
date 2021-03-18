# Backlog de time

## Histórico de versão

| Data | Versão | Descrição | Autor|
| - | - | - | - |
| 25/02/21 | 0.1 | Criação do documento, definição dos épicos, das features  e das histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 26/02/2021 | 0.2 | Adição da priorização nas histórias de usuário | João Vitor Lopes, Rhuan Marques e Sara Campos |
| 02/03/2021 | 0.3 | Adição dos tipos de usuários | Rhuan Marques, Júlio Schneider e Sara Campos |
| 05/03/2021 | 0.4 | Atualização do documento para o Safe essentials | Rhuan Marques, Júlio Schneider e Sara Campos |
| 18/03/2021 | 0.5 | Adição de épicos e conversão em um único documento | João Vitor Lopes, Júlio Schneider e Sara Campos |

## Épicos

| Número | Épico |
|--------|-------|
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | Gerenciamento de usuários |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | Gerenciamento de publicações |
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | Apresentação de recursos do campus FGA |
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | Gerenciamento de fóruns |

## Features 

| Épico | Número | Feature | Benéficios | Critérios de aceitação | Requisitos não funcionais |
| - | - | - | - | - | - |
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | Cadastrar usuário | - Diferenciar usuários<br> - Dar permissões de acordo com o tipo de usuário | - fazer o registro do usuário com seu respectivo tipo <br> - fazer edição do registro  | - armazenar dados do usuário <br> - segurança dos dados do usuário |
| [E01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/51) | [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | Fazer login  | - Identificar um usuário de acordo com seus dados | - relacionar os dados de login com os dados do usuário   | - autenticar o usuário  |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | Publicar notícias | - Funcionalidade necessária ao produto | - permitir a criação da notícia   | - Armazenar uma notícia  |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | Filtrar publicações (notícias e eventos) | - Funcionalidade que agrega valor ao produto | - ter acesso a publicações específicas    | - buscar uma notícia filtrada no banco de dados |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | Visualizar notícias | - Funcionalidade que agrega valor ao produto | - ter acesso a publicações específicas | - buscar uma notícia filtrada no banco de dados |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | Publicar eventos | - Funcionalidade necessária ao produto | - permitir a criação do evento | - armazenar o evento |
| [E02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/52) | [F07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/14) | Visualizar eventos | - Funcionalidade necessária ao produto | - permitir que outros usuários tenham acesso ao evento | - buscar um evento no banco de dados |
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | Visualizar mapa com fotos | - Funcionalidade que agrega valor ao produto | - permitir que outros usuários tenham acesso ao mapa da FGA com fotos do local  |
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | Registrar EJ/EC/Lab | - Funcionalidade necessária ao produto | - permitir que o usuário registre os dados de um EJ/EC/Laboratório da FGA | armazenar dados registrados da EJ/EC/Lab no banco de dados |
| [E03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/53) | [F10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/9) | Visualizar dados da EJ/EC/Lab | - Funcionalidade necessária ao produto | - permitir que outros usuários tenham acesso aos dados de uma EJ/EC/Lab | buscar a EJ/EC/Lab no banco de dados |
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | Criar tópico de discussão no fórum | - Funcionalidade necessária ao produto | - permitir a criação de um tópico de discussão no fórum | - armazenar o tópico no banco de dados  |
| [E04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/54) | [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | Visualizar tópicos de discussão | - Funcionalidade necessária ao produto | - permitir que outros usuários tenham acesso ao fórum | - buscar os tópicos em discussão no banco de dados  |


## Critérios técnicos das histórias de usuário

- Cobertura de testes unitários maior que 80%
- Lint

## Histórias de usuário 

| Feature | US | Critérios de aceitação | História de usuário |
| - | - | - | - |  
| [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | [US01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/23) | - Criação da página do formulário de registro <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como visitante desejo realizar cadastro no site para poder ter acesso com privilégio |
| [F01](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/7) | [US02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/26) | - Criação da página do formulário de registro <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como participante desejo solicitar acesso como gestor para criar publicações e/ou tópicos de fórum |
| [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | [US03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/29) | - Criação da página de login <br> - Envio do formulário de login <br> - Autenticação dos dados de login |  Eu como administrador/gestor/participante desejo logar no meu perfil com o objetivo de realizar alguma ação que requer autenticação |
| [F02](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/8) | [US04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/33) | - Criação da página de resgatar senha <br> - Envio do email de recuperação de senha do usuário <br> - Formulário de troca de senha | Eu como administrador/gestor/participante desejo resgatar minha senha  com o objetivo de fazer login |
| [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | [US05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/36) | - Criação da página de formulário de publicação de notícias <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo criar uma notícia com o objetivo de publicar novas informações |
| [F03](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/10) | [US06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/38) | - Recepção dos dados que devem ser excluídos | Eu como administrador/gestor desejo excluir uma notícia com o objetivo de remover a informação |
| [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | [US07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/39) | - Registro das informações para filtragem das notícias no banco de dados | Eu como administrador/gestor desejo selecionar filtros (data, palavra-chave) para a publicação  com o objetivo de facilitar acesso para os usuários |
| [F04](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/13) | [US08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/40) | - Busca das notícias no banco de dados baseado no filtro selecionado | Eu como visitante desejo filtrar as publicações com o intuito de visualizar publicações de caráter específico |
| [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | [US09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/41) | - Criação da página de notícias <br> - Disponibilização de notícias relevantes (por tempo e popularidade) | Eu como visitante desejo visualizar notícias com o objetivo de me informar |
| [F05](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/11) | [US10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/42) | - Criação da página de formulário de denúncia <br> - Envio do formulário de denúncia para o banco de dados <br> - Disponibilização da denúncia para o administrador | Eu como visitante desejo denunciar uma notícia com o objetivo de alertar os administradores sobre seu conteúdo |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/37) | - Criação da página de formulário de publicação de eventos <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo publicar um evento com o objetivo de manter as pessoas a par de novos eventos |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/35) | - Recepção dos dados que devem ser excluídos | Eu como administrador desejo excluir um evento com o objetivo de retirar da página |
| [F06](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/12) | [US13](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/34) | - Criação da página de formulário de alteração de dados <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser alterados | Eu como administrador/gestor desejo editar dados de um evento com o objetivo de manter a publicação atualizada |
| [F07](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/14) | [US14](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/32) | - Criação da página de eventos <br> - Disponibilização de eventos relevantes (por tempo e popularidade) <br> | Eu como visitante desejo visualizar um evento com o objetivo de acessar as informações sobre o mesmo |
| [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | [US15](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/31) | - Criação da página do mapa | Eu como visitante desejo visualizar o mapa da FGA com o objetivo de me localizar |
| [F08](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/15) | [US16](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/30) | - Criação da página de galeria de fotos <br> | Eu como visitante desejo acessar uma galeria de fotos da FGA com o objetivo de  conhecer  o espaço do campi |
| [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | [US17](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/28) | - Criação da página de formulário de registro de EJ/EC/Lab <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser salvos | Eu como administrador/gestor desejo registrar uma empresa júnior/equipe de competição/laboratório com o objetivo de expô-la no site |
| [F09](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/16) | [US18](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/27) | - Criação da página de formulário de alteração de dados <br> - Envio do formulário ao banco de dados <br> - Recepção dos dados que devem ser alterados | Eu como administrador/gestor desejo atualizar os dados de uma EJ/EC/Lab com o objetivo de manter o registro e informações atualizados | 
| [F10](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/9) | [US19](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/25) | - Criação da página da EJ/EC/Lab | Eu como visitante desejo ter acesso aos dados das EJs/ECs/Lab com o intuito de me informar sobre a equipe |
| [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | [US20](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/24) | - Criação do formulário do tópico de discussão <br> - Criação da página do tópico de discussão | Eu como administrador/gestor desejo criar um tópico de discussão com o objetivo de promover interação sobre um  assunto |
| [F11](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/17) | [US21](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/22) | - Recepção dos dados que devem ser excluídos | Eu como administrador desejo deletar um tópico de discussão com o objetivo de desfazer/encerrar o debate |
| [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | [US22](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/21) | - Criação da página de formulário de denúncia <br> - Envio do formulário de denúncia para o banco de dados <br> - Disponibilização da denúncia para o administrador | Eu como visitante desejo denunciar um tópico/comentário do fórum com o objetivo de solicitar revisão dos administradores |
| [F12](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/18) | [US23](https://github.com/Conecta-UnB/Conecta-UnB-Wiki/issues/19) | - Envio do comentário do usuário ao banco de dados <br> - Disponibilização do comentário do usuário | Eu como participante desejo comentar num tópico de discussão com o objetivo de interagir num debate |
