# CLAUDE.md — arca-app-home

As diretrizes do AGENTS.md valem para todos os agentes de IA, incluindo Claude.

## OpenSpec — fluxo de mudanças compartilhado entre agentes

- Mudança mediana ou grande passa pelo OpenSpec (`openspec/`): nova capability,
  mudança de comportamento ou estratégia, estudo com pré-registro, ou mudança
  multi-arquivo. Fluxo: proposal (`openspec instructions proposal`) → aprovação
  do operador → specs, design e tasks → apply → `openspec archive`.
- Fix trivial e hotfix de produção: commit direto, sem proposal.
- Antes de iniciar qualquer trabalho, verificar `openspec/changes/` por mudanças
  em andamento de outros agentes ou sessões.
- Scaffold de proposal é commitado imediatamente após a criação — nunca fica
  untracked.
- Artefatos do OpenSpec em pt-BR. O OpenSpec decide o quê construir; as skills e
  regras de cada agente decidem como.
