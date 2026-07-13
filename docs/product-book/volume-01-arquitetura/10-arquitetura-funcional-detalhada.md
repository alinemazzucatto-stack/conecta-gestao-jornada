# Arquitetura Funcional Detalhada

## Visão por perfil

```mermaid
flowchart LR
    C[Colaborador] --> CP[Registrar e consultar ponto]
    C --> S[Solicitações]
    C --> E[Espelho e banco de horas]
    G[Gestor] --> EQ[Gestão da equipe]
    G --> A[Aprovações]
    G --> ES[Escalas e pendências]
    R[RH] --> CFG[Configurações]
    R --> F[Fechamento]
    R --> REL[Relatórios]
    AD[Administrador] --> SEG[Segurança]
    AD --> INT[Integrações]
```

## Módulos

| Módulo | Funções |
|---|---|
| Dashboard | KPIs, alertas e IA |
| Controle de Ponto | Registro e histórico |
| Jornadas | Regras e vigências |
| Escalas | Turnos, folgas e plantões |
| Banco de Horas | Saldo e compensações |
| Ocorrências | Detecção e tratamento |
| Solicitações | Ajustes e justificativas |
| Aprovações | Fila, alçada e histórico |
| Espelho | Competência e assinatura |
| Fechamento | Consolidação e bloqueio |
| Relatórios | Operacionais e gerenciais |
| Configurações | Regras e integrações |
| Auditoria | Logs e evidências |
| Conecta AI | Insights e previsões |
