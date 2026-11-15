# intake-adapter

Fronteira de confiança na frente do Argo Workflows: autenticação da origem, normalização para CloudEvents, dedup com janela, limites de tempestade e kill switch. Um adapter por fonte (Grafana, Azure Monitor, Datadog se houver).

## Estado

Esqueleto inicial, sem implementação. Etapas do plano: P3. Decisões relacionadas: D-04, D-10, D-21, D-22, D-36.

## Contexto

Este repositório faz parte do laboratório open-eda-labs: workflows agênticos disparados por eventos, com Argo Workflows e padrões abertos. Cada peça trocável é um repositório que só depende do contrato versionado em `triage-contract` (D-01, D-27).

A fonte da verdade é o [Plano Mestre](https://github.com/open-eda-labs/open-eda-labs.github.io/blob/main/docs/PLANO_MESTRE.md).

As regras do laboratório valem para todos os repositórios e estão no [perfil da organização](https://github.com/open-eda-labs).
