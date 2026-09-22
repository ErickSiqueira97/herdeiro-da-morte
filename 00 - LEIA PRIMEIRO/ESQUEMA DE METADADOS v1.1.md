---
id: esquema-metadados-v1-1
tipo: governanca
schema_version: 1.1
tags: [hdma/governanca]
---
# Esquema de Metadados v1.1

Este arquivo define a camada estrutural para navegação por IA. Ele não altera o cânone narrativo.

## Campos
- `id`: identificador estável derivado do caminho original da nota.
- `tipo`: classe estrutural da nota.
- `schema_version`: versão do esquema estrutural.
- `aliases`: nomes de navegação.
- `tags`: classificação técnica `hdma/*`.
- `moc`: mapa de conteúdo principal.
- `status`: status canônico já existente; nunca deve ser promovido automaticamente.
- `relacoes`: relações explícitas. Na migração v1.1, WikiLinks existentes foram registrados como `tipo: referencia`; tipos semânticos mais específicos só devem ser adicionados quando sustentados pelo conteúdo.

## Regra de autoridade
Metadados servem para localizar e relacionar informação. Em qualquer conflito, o texto da nota, [[REGRAS DE CANON]] e [[BÍBLIA CANÔNICA]] prevalecem.

## Tipos recomendados para relações futuras
`sucessor_de`, `herdeiro_de`, `contraparte_de`, `aliado_de`, `opositor_de`, `membro_de`, `participa_de`, `causa`, `consequencia_de`, `pista_para`, `revela`, `fonte_de_autoridade`, `relacionamento`, `referencia`.

Não inferir esses tipos apenas pelo nome dos arquivos.
