# Arquitetura Técnica

```mermaid
flowchart TB
    WEB[Web] --> GW[API Gateway]
    MOB[Mobile] --> GW
    KIOSK[Kiosk] --> GW
    GW --> AUTH[Identidade]
    GW --> CORE[Serviços de Domínio]
    CORE --> RULES[Motor de Regras]
    CORE --> DB[(Banco)]
    CORE --> CACHE[(Cache)]
    CORE --> FILES[(Evidências)]
    CORE --> Q[Fila de Eventos]
    Q --> ANA[Analytics]
    Q --> INT[Integrações]
    ANA --> AI[Conecta AI]
    CORE --> OBS[Observabilidade]
```

## Requisitos não funcionais

- disponibilidade alvo de 99,9%;
- isolamento multiempresa;
- criptografia em trânsito e repouso;
- idempotência;
- rastreabilidade por `correlation_id`;
- filas com retentativa;
- backup automático;
- suporte a fusos horários;
- interface responsiva.
