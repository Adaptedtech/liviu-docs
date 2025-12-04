# API — Liviu Flow

A API do Liviu Flow fornece todos os recursos necessários para criar, gerenciar e acompanhar projetos, tarefas, fluxos de trabalho e integrações com o Liviu Content.  
Ela é consumida principalmente pelo frontend do Flow, pelo Liviu Content e por sistemas internos de automação.

Esta documentação descreve os principais endpoints, regras de negócio, payloads e estruturas de dados.

---


## Arquitetura da API

-   **Framework:** FastAPI
-   **Padrão:** REST
-   **Autenticação:** JWT (Auth/SSO AdaptEdTech)
-   **Permissões:** Attribute-Based
-   **Formato:** JSON
-   **Padrão de filtros:** Query params
-   **CORS:** habilitado para domínios do ecossistema Liviu

---

# Autenticação

A API só aceita requisições autenticadas via **Bearer Token**:

Authorization: Bearer `<SEU_JWT>`

O token inclui:

-   empresa (tenant)
-   escopos (`Content:read`)
-   roles (`admin`, `gestor`, etc.)
-   usuário

Se o token for inválido/expirado:

-   **401 Unauthorized**
-   ou **403 Forbidden**

---

# Endpoints

<swagger-ui src="../../assets/json/flow/openapi.json"></swagger-ui>
