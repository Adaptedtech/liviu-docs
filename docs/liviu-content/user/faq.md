# FAQ — Liviu Content

Perguntas frequentes sobre o uso do **Liviu Content**, a plataforma de criação e gestão de conteúdos educacionais da AdaptEdTech.

Este FAQ foi estruturado para ajudar usuários iniciantes e avançados a resolverem dúvidas rapidamente.

---

## Acesso e Login

### **1. Não consigo acessar o Liviu Content. O que faço?**

-   Verifique se sua empresa já habilitou o acesso.
-   Confirme suas credenciais no SSO AdaptEdTech.
-   Teste acessar outro módulo (LMS/Analytics).
-   Se não funcionar, abra um ticket no suporte.

---

### **2. Fiz login mas a tela fica carregando para sempre.**

Isso pode ocorrer por:

-   Token expirado
-   Bloqueio de pop-ups do navegador
-   Conexão instável

**Solução:**  
Saia da conta → limpe o cache → entre novamente.

---

### **3. Como altero minha senha?**

A senha é gerenciada pelo **SSO AdaptEdTech**.  
Acesse: **Configurações da Conta → Segurança**.

---

## Criação e Edição de Conteúdos

### **4. Meu conteúdo não está salvando. Por quê?**

Possíveis causas:

-   Internet instável
-   Duas janelas abertas do mesmo conteúdo
-   Erro de sessão expirada

**Solução recomendada:**

-   Atualizar a página
-   Verificar conexão
-   Fechar outras abas do mesmo conteúdo

---

### **5. Perdi alterações no conteúdo. Consigo recuperar?**

Sim. O Liviu Content possui **controle de versões**.  
Vá em:

```text
Conteúdo → Histórico de Versões → Restaurar
```

---

### **6. Como adiciono imagens, vídeos ou PDFs?**

Clique no botão **“+”** → selecione o tipo de bloco → faça upload.

Formatos suportados:

-   JPG / PNG
-   MP4
-   PDF
-   GIF
-   WebM

---

### **7. Posso duplicar um conteúdo?**

Sim!  
Use a opção **“Duplicar”** no menu de ações do conteúdo.

---

# 📚 Estrutura e Organização

### **8. Qual a estrutura recomendada para cursos?**

```text
Curso
 └─ Módulos
      └─ Unidades
           └─ Aulas
                └─ Seções
                     └─ Blocos

```

---

### **9. Como reorganizar módulos e aulas?**

Use drag & drop (arrastar e soltar) na árvore lateral.

---

### **10. O que são Templates?**

Modelos prontos para:

-   Introduções
-   Objetivos
-   Resumos
-   Aulas completas
-   Quizzes

Eles aceleram a produção e garantem padronização.

---

## Colaboração e Revisão

### **11. Como funciona o fluxo de revisão?**

O conteúdo passa por 5 status:

-   Rascunho
-   Em revisão
-   Ajustes necessários
-   Aprovado
-   Publicado

---

### **12. Posso comentar diretamente no conteúdo?**

Sim. Use a área de comentários para revisão colaborativa.

---

### **13. Como saber quem fez qual alteração?**

Use o Histórico de Versões, que mostra:

-   autor da alteração
-   data/hora
-   o que mudou

---

## Publicação e Exportação

### **14. Como publicar no LMS?**

No conteúdo → clique em Publicar → escolha:

-   trilha
-   curso
-   categoria
-   grupos
-   versão

Confirme e aguarde a instalação.

---

### **15. Preciso publicar todas as aulas de uma vez?**

Não. Você pode publicar por partes:

-   por módulo
-   por unidade
-   por atualização incremental

---

### **16. Consigo exportar SCORM?**

Sim — caso habilitado para sua instituição.

Vá em:

```text
Exportar → SCORM 1.2 / 2004
```

---

## **17. Posso exportar para PDF?**

Sim, se a empresa possuir o módulo premium de exportação.

---

## Integração com o Liviu Analytics

### **18. Como vejo o desempenho do conteúdo publicado?**

Através do Liviu Analytics:

-   Engajamento
-   Conclusão
-   Tempo de estudo
-   Performance em quizzes
-   Indicadores por módulo/unidade

---

### **19. O que preciso fazer para enviar dados ao Analytics?**

Nada!
O Liviu Content integra com o LMS e envia eventos SCORM/xAPI automaticamente.

---

## Erros Comuns e Soluções

### **20. Minha imagem não aparece.**

Verifique:

-   tamanho máximo (normalmente 5MB)
-   formato (PNG/JPG)
-   se a internet foi interrompida durante o upload

---

### **21. O conteúdo travou, não responde.**

Tente:

-   Recarregar a página
-   Fechar outras abas pesadas
-   Verificar memória do navegador
-   Sair e entrar novamente

---

### **22. Aparece "Token inválido" ou "Sessão expirada".**

O token de autenticação venceu.
Faça login de novo.

---

## Suporte

Em caso de problemas:

-   Consulte a documentação
-   Use o botão Ajuda no menu lateral
-   Acesse a central de suporte AdaptEdTech
-   Abra um ticket informando:
    -   usuário
    -   instituição
    -   print do erro
    -   passos para reproduzir
