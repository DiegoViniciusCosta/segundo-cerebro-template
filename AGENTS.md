# AGENTS.md

Este repositório é o segundo cérebro do squad: a fonte de verdade sobre o negócio e a técnica de uma jornada do produto. Responda **somente** com base nestas notas.

## Mapa das notas

| Nota | Consulte quando a pergunta for sobre |
|------|--------------------------------------|
| [01 Visão do produto](negocio/01-visao-produto.md) | propósito, público, valor, o que está fora do escopo, quem envolver |
| [02 Glossário](negocio/02-glossario.md) | significado de termo ou sigla, nome do conceito no código |
| [03 Jornada principal](negocio/03-jornada-principal.md) | o que acontece em cada passo, regras de negócio (`RN-xx`), erros esperados |
| [04 Mapa de componentes](tecnico/04-mapa-componentes.md) | qual peça implementa um passo, repositório, integrações, dono |
| [05 Setup e fluxo de dev](tecnico/05-setup-dev.md) | rodar, testar, branches, PR, ambientes, pipeline |
| [06 Decisões e armadilhas](tecnico/06-decisoes-armadilhas.md) | por que algo é assim (`D-xx`), comportamentos estranhos (`A-xx`) |

## Como responder

1. Leia o [glossário](negocio/02-glossario.md) e traduza os termos da pergunta para o sentido deste squad.
2. Abra as notas indicadas no mapa. Se a pergunta cruza negócio e técnica, siga os links entre o passo da jornada (03) e o componente (04).
3. Leia o frontmatter de cada nota usada. Se o `status` for `rascunho` ou `suspeito`, avise na resposta.
4. Responda citando cada nota usada com o seu `revisado_em` e, quando houver, o ID da regra (`RN-xx`, `D-xx`, `A-xx`) e a origem dela.

A resposta está pronta quando cada afirmação tem uma nota citada. Se alguma parte não tiver uma nota que a sustente, diga explicitamente que essa parte não está documentada e indique a nota onde ela deveria estar.

## Ao editar notas

Siga as convenções do [README](README.md#convenções): frontmatter completo, origem em toda regra, links relativos nos dois sentidos (jornada ↔ componente) e `revisado_em` com a data da edição. Mantenha o conteúdo livre de dados de cliente, credenciais, URLs internas sensíveis e valores de produção.
