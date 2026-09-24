# Colinha Eleições SP 2026

Página estática para montar e imprimir a colinha das eleições de 2026 em São Paulo, com foto dos candidatos, filtro por partido e os 6 cargos na ordem da urna.

**Revisado por IA. Pode conter informações incorretas. Verifique** cada número no [DivulgaCandContas do TSE](https://divulgacandcontas.tse.jus.br/) antes de votar.

- Nada vem pré-selecionado. As escolhas ficam salvas só no navegador de quem usa (`localStorage`).
- Dados e fotos: TSE, obtidos via [colinha.ai](https://colinha.ai) em 24/09/2026.
- Candidatos que renunciaram ou tiveram o registro negado em definitivo não aparecem. Registros negados com recurso pendente aparecem marcados como "sub judice".

## Estrutura

- `index.html`: a página.
- `candidatos.js`: dados gerados (número, nome, partido, situação).
- `fotos/`, `partidos/`: imagens dos candidatos e logos dos partidos.
- `data/raw*.jsonl`: dados brutos por cargo (1 presidente, 3 governador, 5 senador, 6 dep. federal, 7 dep. estadual).

## Contribuir

Achou um número, nome ou foto errado? Abra uma issue ou um pull request.

Página independente, sem ligação com partidos ou candidatos.
