# Diagrama de Contexto (C1)

```mermaid
graph TB
Gestor[Gestor do Cliente / Tenant]
Operador[Operador do Cliente]
Admin[Admin da Plataforma]
SaaS[SaaS Gestão de Serviços]
Gateway[Gateway de Pagamento]
Email[Serviço de E-mail/SMS]

Gestor -- "Consulta dashboards" --> SaaS
Operador -- "Cria e gerencia OS" --> SaaS
Admin -- "Gerencia usuários" --> SaaS
SaaS -- "Processa pagamentos" --> Gateway
SaaS -- "Envia notificações" --> EmailS
