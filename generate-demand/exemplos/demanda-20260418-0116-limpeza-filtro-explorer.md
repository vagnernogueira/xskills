# Template SIMPLES

## Contexto de execução da IA

- Pacote de contexto: `_docs/ia-context/README.md`
- Regras globais: `_docs/ia-context/core/rules.md`
- Regras do projeto: `_docs/ia-context/project-overlay/rules.md`
- Contexto do projeto: `_docs/ia-context/project-overlay/context.md`
- Workflow base: `_docs/ia-context/core/workflow.md`
- Contrato de saída: `_docs/ia-context/core/output-contracts.md`

## Instruções

- Use `core/rules.md` e o contexto do overlay de projeto.
- Faça apenas o escopo solicitado, com mudanças mínimas.
- Não invente fatos; explicite suposições.

## Demanda

Ajustar o texto do botão de limpeza do filtro no Explorer para usar a label `Limpar filtro` em vez do texto atual, preservando o comportamento existente do clique e sem alterar layout, ícone, atalhos ou qualquer outra ação do componente. A mudança deve ficar restrita ao frontend e apenas ao ponto em que a label é renderizada.

## Planejamento da execução

1. Localizar o ponto de renderização da label do botão de limpeza do filtro em `Explorer.vue` (ou no componente filho responsável).
2. Substituir o texto atual pela string `Limpar filtro`, preservando o handler de clique e todos os demais atributos do elemento.
3. Validar visualmente que a nova label é exibida corretamente e que o comportamento de clique permanece idêntico ao estado anterior.

## Memorial de execução

> Memorial pendente. Ao final da execução ou atendimento da demanda, adicione o resumo da execução, a lista de arquivos alterados e as validações recomendadas.

### Sugestão de commit final

> Mensagem de commit pendente. Use a skill conventional-commits para sugerir a mensagem final.