# Arquitetura Corporativa

```mermaid
flowchart TB
    S[Estratégia] --> B[Processos de Negócio]
    B --> A[Aplicações e Serviços]
    A --> D[Dados e Analytics]
    D --> T[Infraestrutura]
    G[Governança e Segurança] -. supervisiona .-> S
    G -. supervisiona .-> B
    G -. supervisiona .-> A
    G -. supervisiona .-> D
    G -. supervisiona .-> T
```

## Capacidades de negócio

| Capacidade | Resultado esperado |
|---|---|
| Registrar jornada | Marcações confiáveis |
| Planejar escalas | Cobertura operacional |
| Apurar horas | Cálculo consistente |
| Tratar exceções | Ajustes rastreáveis |
| Aprovar solicitações | Decisão por alçada |
| Fechar competência | Consolidação segura |
| Integrar folha | Eventos corretos |
| Monitorar indicadores | Visão em tempo real |
| Auditar operações | Evidências completas |
