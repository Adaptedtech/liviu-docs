# Portal de Documentação do LiviuHub

Bem-vindo ao **Portal de Documentação da LiviuHub**.  
Aqui você encontra toda a documentação oficial dos nossos produtos — organizada, atualizada e pensada para facilitar o trabalho de usuários, desenvolvedores e clientes.

Este portal segue a metodologia **Docs-as-Code**, garantindo que cada atualização de software venha acompanhada da documentação correspondente.

---

## Produtos Documentados

### **Liviu Analytics**

Documentação completa incluindo:

-   Usuário:

    -   Primeiros Passos
    -   Guia do Usuário
    -   Fluxos
    -   FAQ

-   Desenvolvedores:
    -   Arquitetura
    -   API
    -   Frontend

👉 _Acesse no menu superior ou clique aqui:_ **[Documentação Liviu Analytics](liviu-analytics/index.md)**

---

### **Liviu Content**

Inclui:

-   Usuário:

    -   Primeiros Passos
    -   Guia do Usuário
    -   Fluxos
    -   FAQ

-   Desenvolvedores:
    -   Arquitetura
    -   API
    -   Frontend

👉 _Acesse no menu superior ou clique aqui:_ **[Documentação Liviu Content](liviu-content/index.md)**

---

### **Liviu Flow**

Inclui:

-   Usuário:

    -   Primeiros Passos
    -   Guia do Usuário
    -   Fluxos
    -   FAQ

-   Documentação Técnica:
    -   Arquitetura
    -   API
    -   Frontend

👉 _Acesse no menu superior ou clique aqui:_ **[Documentação Liviu Flow](liviu-flow/index.md)**

---

## Como navegar neste portal

Use o menu superior para navegar entre:

-   Inicio
-   Liviu Analytics
-   Liviu Content
-   Liviu Flow

E use o menu lateral esquerdo para navegar entre:

-   **Início**
-   **Usuários**

    -   Primeiros Passos
    -   Guia do Usuário
    -   Fluxos
    -   FAQ

-   **Documentação Técnica**
    -   Arquitetura
    -   API
    -   Frontend

Todas as páginas são criadas com foco em clareza, escala e experiência do usuário.

---

## Como contribuir

Este portal utiliza **MkDocs + Material**, seguindo o conceito de documentação contínua.

Para editar ou escrever conteúdo:

```bash
mkdocs serve
```

O site será recarregado automaticamente conforme você modifica arquivos `.md`

Após finalizar:

```bash
git add .
git commit -m "Atualiza documentação"
git push
```

O deploy acontece automaticamente via GitHub Actions - garantindo que o portal esteja sempre atualizado.

---

## Estrutura do projeto

```text
docs/
    index.md
    liviu-analytics/
    liviu-content/
    liviu-flow/
```

Cada produto possui:

-   `user/` -> documentação do usuário
-   `tech/` -> documentação técnica
-   `tech/api/` -> Swagger/OpenAPI/ endpoints
-   `arquitetura.md` -> Diagramas mermaid
-   `frontend.md` / `backend.md`

---

## Sobre a AdaptEdTech

A AdaptEdTech cria soluções tecnológicas e educacionais que simplificam processos, potencializam resultados e tornam o ensino e o desenvolvimento profissional mais acessíveis, eficientes e escaláveis.

Nosso compromisso é entregar produtos de alta qualidade acompanhados por uma documentação clara, completa e fácil de utilizar.

---

Se tiver dúvidas, sugestões ou desejar contribuir com melhorias, entre em contato com nossa equipe.

Boa navegação!
