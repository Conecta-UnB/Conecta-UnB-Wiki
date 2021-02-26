
# Visão do projeto

## Histórico de versão

| Data | Versão | Descrição | Autor |
|--------|-----------|---------------|---------|
| 11/02/2021 | 0.1 | Proposta de projeto e criação do documento | Edvan Gomes<br> Rhuam Marques<br> João Lopes<br> Júlio Schneider<br> Sara Campos |
| 17/02/2021 | 1.0 | Finalização do documento | Júlio Schneider<br> Sara Campo<br> João Lopes |

## Introdução

### Declaração do problema

| Declaração | Especificação |
|--------|-----------|
| O problema | A falta de uma plataforma que promova a centralização de comunicados e a interação dos discentes, docentes e a comunidade da FGA. |
| Afeta | Os estudantes, organizações institucionais da universidade e a comunidade. |
| Cujo impacto é | O problema muitas vezes faz com que informações relevantes sejam dispersas por diversos meios de comunicação, não atingindo boa parte da comunidade da FGA. |
| Uma solução de sucesso seria | Uma aplicação que consiga integrar e promover a interação entre as partes através da disponibilização de informações de maneira funcional e organizada. |

### Objetivos do projeto

Tendo em vista a carência de uma base informativa que permita uma comunicação eficiente entre a comunidade do campus FGA, a motivação do projeto é fornecer uma plataforma na qual os usuários, tanto do meio acadêmico quanto exteriores a ele, possam interagir e divulgar informações de relevância à comunidade da FGA. Dessa forma, busca-se um meio de concentrar e organizar a divulgação de comunicados, facilitando a correspondência entre as partes.

## Stakeholders

| Nome | Descrição | Responsabilidades |
|--------|-----------|---------------|
| Discentes | Estudantes matriculados na FGA. | Promover a interação entre os demais usuários.<br> São os principais divulgadores e alvos das notícias. |
| Docentes | Professores que trabalham na FGA. | Disponibilizar informações importantes para os demais usuários. |
| Empresas Juniores, Equipes de Competição e Laboratórios | Grupos associados à faculdade. | Promover eventos.<br> Disponibilizar informações e notícias sobre os serviços e produtos fornecidos.|

## Visão geral do produto

### Declaração da posição do produto

| Declaração | Especificação |
|--------|-----------|
| Para | a comunidade da FGA e interessados |
| Quem | deseja se informar |
| O ConectaUnb | é uma aplicação web |
| Que | centraliza e organiza os comunicados |
| Ao contrário | do grupo da FGA no Facebook |
| Nosso produto | torna prático o acesso às informações e notícias. |

### Mínimo produto viável

O ConectaUnb é uma plataforma web que permite que os usuários publiquem informações relevantes sobre a comunidade da FGA. Para isso é necessário uma página web que permita aos usuários ter acesso a esses avisos de forma organizada, ainda que possa controlar quem pode postar avisos nessa página. Desta forma, o sistema centraliza essas informações que normalmente estão dispersas em vários meios de comunicação.

## Visão geral do produto

### Organização do Projeto

| Papel | Atribuições | Responsável | Participantes |
|--------|-----------|---------------|---------|
| Scrum Master | O Scrum Master é responsável por garantir que a equipe siga os valores do SCRUM, atua também para remover obstáculos à equipe de desenvolvimento. Ainda é um facilitador das dailies e reuniões de sprint. | O papel de Scrum Master será rotacionado pela equipe desenvolvimento | - |
| Product Owner | É o responsável pelo gerenciamento do backlog do produto. Além disso, deve garantir que as funcionalidades adicionadas estejam conceitualmente de acordo com o backlog do produto. | O papel de Product Owner será rotacionado pela equipe desenvolvimento | - |
| Desenvolvedores | Responsáveis pelo desenvolvimento do software, e como não há designers no time, também é papel do desenvolvedor, estruturar o design do projeto.  | Todos os membros da equipe são desenvolvedores | Toda a equipe |

## Ferramenta, ambiente e infraestrutura

### Hardware

| Perfil | Tipo de Hardware | Configurações | Qtd. Planejada | Prazo Estimado | Observação |
|--------|-----------|---------------|---------|---------|---------|
| Desenvolvedor  | Computador | - i5 5ª geração<br>- 4GB de Ram| 05 | 22/05/2021 |

### Softaware

| Perfil | Tipo de software | Nome da ferramente | Versão | Qtd. licenças planejas | Prazo Estimado | Observação |
|--------|-----------|---------------|---------|---------|---------|---------|
| Todos os perfis planejados  | Repositório para código e documentação | Github | - | N/A | 22/05/2021 |
| Todos os perfis planejados  | Serviço de armazenamento e compartilhamento de arquivos | Google Drive | - | N/A | 22/05/2021 |
| Todos os perfis planejados  | Editor de código-fonte | VS Code | 1.53.0 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Linguagem de programação | JavaScript | ECMAScript  6 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Biblioteca JavaScript para criar interfaces | React | 17.0.0 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Framework JavaScript para backend | Node.js | 14.15.5 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Sistema gerenciador de banco de dados | PostgreSQL | 13.2 | N/A | 22/05/2021 |
| Todos os perfis planejados  | ORM para Node.js | Sequelize | v6 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Gerenciador de banco de dados PostgreSQL | PostBird | v11 | N/A | 22/05/2021 |
| Todos os perfis planejados  | Cliente desktop API para Rest e GraphQL | Insomnia | 2020.5 | N/A | 22/05/2021 |

## Processo de gerência do projeto

### Planejamento das fases e iterações do projeto

O projeto será feito de acordo com o metodologia SCRUM, tendo período de Sprint de uma semana, onde ao final da sprint deve-se gerar um artefato que agrega ao produto, logo um modelo incremental, a Sprint 0 do projeto teve início no dia 14 de fevereiro. Além disso, pelo projeto estar ligado à disciplina de Requisitos da UNB - FGA, será necessário gerar certos produtos de acordo com a necessidade da disciplina. Esses produtos e datas são:

* Documento de visão - 18/02
* Backlog do produto - 11/03
* Primeira release - 01/04
* Escopo do Produto - 22/04
* Segunda release - 13/05

### Processo de desenvolvimento e mensuração

Durante o desenvolvimento do projeto serão realizadas reuniões às terças, quintas, para todos os membros da equipe estarem a par do andamento do projeto, além de ser um momento para esclarecer dúvidas e sugerir alterações. Como o tempo de cada Sprint é de uma semana, ao final de cada ciclo, no sábado, será realizada uma reunião de retrospectiva da Sprint finalizada, além de realizar o planejamento da próxima. Nessas reuniões é realizado um planning poker, que estima o valor da história de usuário com pontos de história, os pontos de história são distribuídos de acordo com a tabela abaixo, que segue a sequência de Fibonacci. Na discussão da Sprint anterior é gerado um relatório de velocity, que é a quantidade de pontos de histórias cumpridos por Sprint.

| Pontuação | Significado |
|--------|-----------|
| 1 | Tarefa muito fácil |
| 2 | Tarefa fácil |
| 3 | Tarefa média |
| 5 | Tarefa difícil |
| 8 | Épico |
| 13 | Super-épico |

### Matriz de comunicação

| Descrição | Área/Envolvidos | Periodicidade | Produtos Gerados |
|--------|-----------|---------------|---------|
| - Dailies<br> - Acompanhamento das atividades | Equipe do Projeto | Terças e quintas | - |
| - Fechamento de Sprint<br> -  Definição do pareamento<br> - Planejamento da Sprint seguinte | Equipe do Projeto | Sábado | Ata de reunião |
| - Comunicação geral do grupo, geralmente por aplicativo de mensagens | Equipe do Projeto | Sempre que necessário | - |
| - Registro de questões referentes ao projeto, presente nas issues do repositório da equipe | Equipe do projeto | Sempre que necessário | Registro dessas discussões na própria issue |

### Estabilidade do projeto

São identificados alguns fatores que apontam a probabilidade de alteração do projeto, como mudanças de prazo, débitos técnicos e afins. Conforme as prioridades estabelecidas e os recursos, cabe à equipe compreender o problema e deliberar as ações a serem tomadas para seguir com o desenvolvimento pleno do projeto. A cada sprint, essas incertezas serão discutidas coletivamente, pretendendo sempre manter estável o decorrer do projeto. 

### Gerenciamento de riscos

| Risco | Descrição | Probabilidade | Impacto |
|--------|-----------|---------------|---------|
| Dificuldade de desenvolvimento do software | Caso o tema escolhido tenha uma alta complexidade ou os membros da equipe não tenham experiência com as tecnologias utilizadas | Alta | 3 |
| Mudança do escopo  | Se porventura a escolha do tema não agrade os membros da equipe ou a proposta seja rejeitada pelo professor   | Baixa | 3 |
| Baixa produtividade da equipe | Questões como disponibilidade de tempo e/ou falta de motivação dos integrantes | Moderada | 1 |
| Ambiente e recursos de trabalho inadequado| Na hipótese de que ocorra problemas com acesso a internet, eficiência dos computadores utilizados pela equipe, espaço de trabalho dos integrantes, e afins | Moderada | 1 |
| Membro ocioso | Se por acaso alguém da equipe está incapaz de realizar as tarefas ou reuniões, seja por desmotivação, falta de conhecimento, falta de recursos ou até mesmo questões pessoais  | Moderada | 2 |
| Um o mais integrantes sairem ou ficarem ausentes | Caso algum membro da equipe deixe o projeto por um tempo, determinado ou não  | Muito baixa | 3 |
| Problema de comunicação na equipe | No caso de haver algum sentimento de não pertencimento ou um conflito de interesses | Moderada | 2 |

| Escala | Impacto |
|--------|-----------|
| 1 | 1 a 2 dias |
| 2 | 3 a 7 dias |
| 3 | 8 dias ou mais |

### Critérios de planejamento

Durante o desenvolvimento, pode ser necessário que uma ou várias histórias, ou features, sejam re-planejadas devido a mudanças nos requisitos. Para isso, essas alterações devem ser analisadas pelo Product Owner, para garantir que atendam a nova composição dos requisitos. Também é importante a presença dos desenvolvedores nessa tarefa, principalmente os que estiveram envolvidos com a feature.

## Precedência e prioridade

A principal função do produto é ser uma plataforma de notícias e eventos relevantes, logo essa seria a maior prioridade e, em segundo lugar, estaria uma parte da plataforma que permitisse a usuários não habituados com o ambiente da FGA, pudessem ter acesso a informações relevantes a eles, como mapa do campus, explicação de cada localização e possivelmente fotos. O projeto também visa possibilitar um maior contato entre os discentes da faculdade e as organizações de alunos, como as empresas juniores e as equipes de competição. Como última prioridade, se tem a possibilidade de criar uma plataforma onde pessoas relacionadas ao campus possam divulgar oportunidades de compras, vendas e trocas.

## Referências

* DOCUMENTO de Visão. [S. l.], 2014. Disponível em: [Visão IBM](https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html). Acesso em: 17 fev. 2021.
* BOURQUE, P.; FAIRLEY, R.E. SWEBOK: Guide to the Software Engineering Body of Knowledge. 3.0. ed. [S. l.]: IEEE Computer Society, 2014. Disponível em: [Swebok](https://www.computer.org/education/bodies-of-knowledge/software-engineering). Acesso em: 17 fev. 2021.