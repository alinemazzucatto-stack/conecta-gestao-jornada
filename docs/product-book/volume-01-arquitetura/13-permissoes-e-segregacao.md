# Permissões e Segregação

Uma permissão combina:

```text
ação + recurso + escopo
```

Exemplo:

```text
aprovar + ajuste_ponto + equipe_direta
```

| Perfil | Escopo |
|---|---|
| Colaborador | Próprios dados |
| Gestor | Equipe autorizada |
| RH | Empresa ou unidades |
| Administrador | Configuração técnica |
| Auditor | Leitura controlada |
| Integração | Ações de máquina |

## Regras

1. Nenhum acesso atravessa empresas.
2. Gestores visualizam apenas equipes vigentes.
3. Permissões temporárias possuem expiração.
4. Ações críticas podem exigir dupla aprovação.
5. Alterações de perfil geram auditoria.
