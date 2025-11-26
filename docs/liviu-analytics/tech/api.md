# API — Liviu Analytics

A **API Liviu Analytics** fornece aos dashboards e integrações externas uma camada unificada para acesso a indicadores de engajamento, conclusão, performance e interações dos alunos.

Ela funciona sobre um banco analítico alimentado **exclusivamente por eventos SCORM/xAPI** enviados pelo LMS.

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
-   escopos (`analytics:read`)
-   roles (`admin`, `gestor`, etc.)
-   usuário

Se o token for inválido/expirado:

-   **401 Unauthorized**
-   ou **403 Forbidden**

---

# Endpoints

<swagger-ui src="../../assets/json/analytics/openapi.json"></swagger-ui>
