# Segundo Cérebro do Squad

Base de conhecimento (negócio + técnico) do squad, escrita para ser consumida por agentes de IA e por pessoas.

## Escopo do MVP

Uma jornada só: **<NOME DA JORNADA>**. Seis notas:

| # | Nota | Camada | Responde |
|---|------|--------|----------|
| 01 | [Visão do produto](negocio/01-visao-produto.md) | Negócio | O que é, pra quem, por que existe |
| 02 | [Glossário](negocio/02-glossario.md) | Negócio | O que cada termo significa aqui |
| 03 | [Jornada principal](negocio/03-jornada-principal.md) | Negócio | O que acontece, passo a passo, e quais regras valem |
| 04 | [Mapa de componentes](tecnico/04-mapa-componentes.md) | Técnico | Que peça implementa cada passo |
| 05 | [Setup e fluxo de dev](tecnico/05-setup-dev.md) | Técnico | Como rodar, testar e subir |
| 06 | [Decisões e armadilhas](tecnico/06-decisoes-armadilhas.md) | Técnico | Por que é assim e onde se queima |

Critério de pronto: [avaliacao/perguntas.md](avaliacao/perguntas.md). O agente precisa acertar pelo menos 8 de 10 respostas usando só estas notas.

## Convenções

- **Frontmatter obrigatório** em toda nota: `dono`, `revisado_em`, `status`.
- `status`: `rascunho` → `revisado` → `suspeito` (fica suspeito se passar de 90 dias sem revisão ou se alguém duvidar do conteúdo).
- **Toda regra de negócio tem origem** (normativo, decisão do PO, regulatório, legado). Regra sem origem fica marcada como `origem: desconhecida`.
- **Links cruzados** com caminho relativo. Cada passo da jornada aponta para o componente que o implementa, e cada componente aponta de volta para os passos que atende.
- **Proibido:** dados de cliente, credenciais, URLs internas sensíveis, valores de produção.
- Comentários `<!-- -->` são instruções do template. Apague depois de preencher.

## Instruções para o agente

Ficam em [AGENTS.md](AGENTS.md).
