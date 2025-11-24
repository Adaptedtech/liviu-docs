# 📘 Portal de Documentação do Ecossistema Liviu

Bem-vindo ao repositório oficial do **Portal de Documentação** da AdaptEdtech.  
Este projeto centraliza toda a documentação dos nossos produtos, incluindo:

- **Documentação do Usuário**
- **Documentação Técnica**
- **Arquitetura**
- **APIs**
- **Front-end**
- **Integrações**
- **Guia de Setup e Desenvolvimento**
- **Referências de código TypeScript (geradas automaticamente)**

Toda a documentação segue o modelo **Docs-as-Code**, utilizando:

- **MkDocs**  
- **Material for MkDocs**  
- **Markdown**  
- **GitHub Pages (deploy automático)**  
- **TypeDoc (para gerar documentação de TypeScript)**  

---

## 🚀 Tecnologias Utilizadas

- **MkDocs** – gerador de site estático  
- **Material for MkDocs** – tema moderno e poderoso  
- **Markdown (.md)** – padrão principal de escrita  
- **TypeDoc** – geração automática de documentação TS  
- **GitHub Actions** – pipeline de build + deploy  
- **GitHub Pages** – hospedagem do portal  

---

## 📁 Estrutura do Repositório

```text
m2-docs/
  mkdocs.yml
  docs/
    index.md

    produto-1/
      index.md
      user/
        guia-usuario.md
        fluxos.md
        faq.md
      tech/
        arquitetura.md
        frontend.md
        api/
          # Gerado automaticamente pelo TypeDoc
        banco-de-dados.md
        integracoes.md

    produto-2/
      ...

    produto-3/
      ...
```

Cada produto possui uma divisão entre:

    - user/ -> documentação do usuário
    - tech/ -> documentação técnica

---

## Como rodar localmente

### 1. Criar ambiente (opcional mas recomendado)

```bash
    python -m venv venv
    source venv/bin/activate
```

### 2. Instalar as dependências

```bash
    pip install mkdocs mkdocs-material
```

### 3. Rodar o servidor local

```bash
    mkdocs serve
```

Acesse:

    - http://127.0.0.1/8000


---

## Deploy automático (GitHub Action)

O deploy acontece automaticamente no **push para a branch** `main`

O workflow está em:

```bash
    .github/workflows/deploy-docs.yml
```

Ele:
    1. Instala MKDocs + Material
    2. Gera o site estático (`mkdocs build`)
    3. Publica na branch `gh-pages`

O portal fica disponivel em

```bash
    https://SEU-USUARIO.github.io/docs/
```

---

## Como contruibuir

### Passo 1 -  Crie uma branch

```bash
    git checkout -b docs/nome-da-secao
```

### Passo 2 - Atualize ou adicione arquivos `.md`

### Passo 3 - Teste localmente

```bash
    mkdocs serve
```

### Passo 4 - Commit + PR

```bash
    git add .
    git commit -m "Atualiza documentação do Produto X"
    git push origin docs/nome-da-secao
```

### Passo 5 - Abra um Pull Request

A documentação só é considerada completa quando:
    - Código alterado -> documentação corresponde atualizada
    - PR contem mudanças em `/docs/..` para aquela feature

---

## Padrões de escrita
- Utilize frases curtas e diretas
- Use exemplos de código sempre que possível
- Inclua prints ou diagramas quando necessários
- Cada página deve começar com um título claro
- Evites siglas sem explicação
- Manteha o idioma consistente (PT-BR)

---

## Licença

Documentação interna da AdaptEdtech - Todos os direitos reservados.

---

