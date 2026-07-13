# Auditoria e Rastreabilidade

## Eventos auditáveis

- login e logout;
- marcações;
- ajustes;
- jornadas e escalas;
- aprovações;
- fechamento e reabertura;
- permissões;
- exportações;
- integrações;
- consultas sensíveis.

## Estrutura mínima

| Campo | Descrição |
|---|---|
| `audit_id` | Identificador |
| `empresa_id` | Tenant |
| `actor_id` | Usuário ou integração |
| `action` | Ação |
| `resource_type` | Entidade |
| `resource_id` | Registro |
| `before_data` | Estado anterior |
| `after_data` | Estado posterior |
| `occurred_at` | Data/hora UTC |
| `ip_address` | Origem |
| `device_info` | Dispositivo |
| `correlation_id` | Rastreabilidade |
| `result` | Resultado |
