# Modelagem do Banco de Dados

## Histórico de versão

| Data | Versão | Descrição | Autor |
| ------ | ---------- | ------------- | -------- |
| 16/03/2021 | 0.1 | Criação do documento | João Lopes e Sara Campos |
| 18/03/2021 | 0.2 | Criação do DE-R | João Lopes, Sara Campos e Júlio Schneider |

   
## Modelo Entidade Relacionamento (ME-R)

### Entidades

* NOTICIA

* EVENTO

* USUARIO

* PESQUISA_EXTENSAO

* FORUM

* COMENTARIO


### Atributos

- **NOTICIA:**  
    → <ins>id</ins>;  
    → titulo;  
    → conteudo;  
    → imagem;  
    → idUser;  
    → autor.    

- **EVENTO:**   
    → <ins>id</ins>;  
    → titulo;  
    → descricao;  
    → imagem;  
    → organizador;  
    → idUser.  

- **USUARIO:**   
    → <ins>matricula</ins>;  
    → *role*;  
    → nome;  
    → email;  
    → senha;  
    → telefone.  

- **PESQUISA_EXTENSAO:**   
    → <ins>id</ins>;  
    → nome;  
    → descricao;  
    → email;  
    → telefone;  
    → facebook;  
    → instagram;  
    → site;  
    → foto;  
    → idUser.  

- **FORUM:**   
    → <ins>id</ins>;  
    → titulo;  
    → descricao;  
    → idUser.  

- **COMENTARIO:**   
    → <ins>id</ins>;  
    → conteudo;  
    → idUser;  
    → idForum.  

### Relacionamentos

* USUARIO - cria - NOTICIA
    - Um usuário cria várias notícias e uma notícia é criada por um usuário
    - Cardinalidade 1:n

* USUARIO - cria - EVENTO
    - Um usuário cria vários eventos e um evento é criado por um usuário
    - Cardinalidade 1:n

* USUARIO - registra - PESQUISA_EXTENSAO
    - Um usuário registra apenas uma pequisa_extensao e uma pesquisa_extensao é registrada por um usuário.
    - Cardinalidade 1:1

* USUARIO - cria - FORUM
    - Um usuário cria vários fóruns e um fórum é criado por um usuário.
    - Cardinalidade 1:n

* USUARIO - realiza - COMENTARIO
    - Um usuário realiza vários comentários e um comentário é realizado por um usuário
    - Cardinalidade 1:n

* COMENTARIO - pertence - FORUM
    - Um comentário pertence a um fórum e um fórum possui vários comentários
    - Cardinalidade 1:n


## Diagrama Entidade Relacionamento (DE-R)

![DE-R](assets/der.png)

