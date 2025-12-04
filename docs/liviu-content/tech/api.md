# API — Liviu Content

A API do Liviu Content é responsável pela criação, edição, organização, versionamento e publicação dos conteúdos educacionais utilizados no ecossistema AdaptEdTech.  
Ela é consumida principalmente pelo frontend do Liviu Content e também por ferramentas internas de integração, como o LMS e o Flow.

Esta documentação descreve os principais endpoints, estruturas de dados e regras de negócio.

---

## Arquitetura da API

-   **Framework:** Node/NestJS
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

<swagger-ui src="../../assets/json/Content/openapi.json"></swagger-ui>
