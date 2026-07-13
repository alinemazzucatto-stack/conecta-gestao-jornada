---
hide:
  - toc
---

<section class="hero-docs">
  <div class="hero-eyebrow">PRODUCT BOOK OFICIAL</div>
  <h1>Conecta Gestão de Jornada</h1>
  <p>Plataforma Enterprise para controle de ponto, escalas, banco de horas, aprovações, auditoria, integrações e inteligência operacional.</p>
  <div class="hero-actions">
    <a class="md-button md-button--primary" href="product-book/">Explorar Product Book</a>
    <a class="md-button" href="product-book/volume-01-arquitetura/">Ver arquitetura</a>
    <a class="md-button" href="roadmap/">Consultar roadmap</a>
  </div>
</section>

<div class="grid cards" markdown>

-   :material-book-open-page-variant-outline:{ .lg .middle } __Product Book__

    ---

    Visão estratégica, arquitetura e especificação oficial do produto.

    [:octicons-arrow-right-24: Acessar](product-book/)

-   :material-database-outline:{ .lg .middle } __Banco de Dados__

    ---

    Entidades, relacionamentos, índices, versionamento e auditoria.

    [:octicons-arrow-right-24: Acessar](banco-de-dados/)

-   :material-api:{ .lg .middle } __APIs e Integrações__

    ---

    Endpoints, autenticação, webhooks, REP e integração com folha.

    [:octicons-arrow-right-24: Acessar](api/)

-   :material-palette-outline:{ .lg .middle } __Design System__

    ---

    Componentes, padrões visuais, acessibilidade e experiência.

    [:octicons-arrow-right-24: Acessar](design-system/)

-   :material-file-sign:{ .lg .middle } __ADRs__

    ---

    Histórico das decisões de produto e arquitetura.

    [:octicons-arrow-right-24: Acessar](adr/)

-   :material-map-marker-path:{ .lg .middle } __Roadmap__

    ---

    Evolução planejada do produto por fases e entregas.

    [:octicons-arrow-right-24: Acessar](roadmap/)

</div>

## Fluxo macro do produto

```mermaid
flowchart LR
    A[Empresa] --> B[Jornadas e escalas]
    B --> C[Colaboradores]
    C --> D[Registro de ponto]
    D --> E[Validação automática]
    E --> F[Aprovações]
    F --> G[Fechamento]
    G --> H[Folha e integrações]
    H --> I[Dashboards e Conecta AI]
```

## Fundamentos

<div class="grid cards" markdown>

-   __Fonte única de dados__

    Informações cadastradas uma vez e reutilizadas por todo o ecossistema.

-   __Auditoria integral__

    Toda ação crítica mantém usuário, data, origem e histórico antes/depois.

-   __Configuração sem código__

    Regras parametrizáveis por empresa, unidade, sindicato, equipe e colaborador.

-   __Arquitetura modular__

    Contratação independente de ponto, escalas, banco de horas, analytics e integrações.

</div>
