# Atualizando Relatório Financeiro com Foco na Experiência do Usuário

Projeto de apoio ao desafio da formação Power BI Analyst da DIO, com base no documento de instruções da atividade.

## Objetivo do desafio

Melhorar a experiência de quem consome o relatório financeiro, considerando:

- Posicionamento dos visuais;
- Contraste;
- Proporção áurea como referência de composição, sem tratá-la como regra rígida;
- Segmentação dos dados;
- Botões e menus de navegação em cada página;
- Destaque visual para foco e seleção.

O material da atividade indica que o relatório final deve ter três páginas.

## Arquivo de origem

`relatorio_financeiro_base.pbix` é uma cópia do relatório enviado para análise e escolhido como ponto de partida. **Ele não foi modificado nem validado no Power BI Desktop neste ambiente.**

A estrutura do arquivo contém duas páginas (`Home page` e `Principal`). A página `Principal` inclui vários visuais de análise, como cartões, gráficos de área e barras, gráfico de rosca, mapa, árvore hierárquica, segmentador de data, formas, imagens e botões.

## Proposta de organização

1. **Home** — página de entrada, com título do relatório, breve contexto e botão para abrir o painel.
2. **Visão geral** — cartões de indicadores na primeira faixa; tendência temporal abaixo; comparações por segmento e produto agrupadas na parte inferior; país em visual próprio. Manter o segmentador de data visível e evitar duplicar indicadores com o mesmo significado.
3. **Detalhamento** — página planejada para a matriz de descrição de vendas e exploração por produto, segmento, país e período, com um menu de navegação consistente com as outras páginas.

## Princípios de UX a verificar

- **Posicionamento:** organizar em faixas e grupos relacionados; manter margens e alinhamentos consistentes.
- **Contraste:** garantir legibilidade de títulos, rótulos, cartões e estados selecionados; não depender apenas da cor para indicar seleção.
- **Proporção:** usar a proporção áurea como referência visual quando fizer sentido, priorizando legibilidade e hierarquia da informação.
- **Segmentação:** manter filtros claros e previsíveis, deixando explícito quando afetam a página inteira ou apenas um visual.
- **Navegação:** ter menus/botões equivalentes em todas as páginas; destacar página atual e testar cada ação.

## Estado do trabalho

Este repositório preparado documenta o ponto de partida e o plano de melhoria. Não declara como concluídas as alterações visuais que ainda precisam ser feitas e verificadas no Power BI Desktop.

Consulte `docs/AUDITORIA_UX.md` para a revisão inicial e `docs/CHECKLIST_ENTREGA.md` para os passos restantes.
