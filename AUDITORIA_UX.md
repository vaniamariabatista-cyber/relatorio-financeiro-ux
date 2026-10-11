# Revisão inicial de UX do relatório

## Escopo observado

O PBIX-base selecionado possui duas páginas. A primeira, `Home page`, contém uma imagem de fundo e um botão de ação. A segunda, `Principal`, contém diversos elementos, entre eles cartões de indicadores, gráfico de área, gráficos de barras, rosca, mapa, árvore hierárquica, segmentador de data, imagens, formas e botões.

Esta revisão foi feita a partir da estrutura do arquivo PBIX e do documento de instruções. Não equivale a validar o resultado renderizado no Power BI Desktop.

## Matriz de requisitos

| Requisito da atividade | Situação identificada | Próxima ação |
|---|---|---|
| Posicionamento | A página Principal concentra muitos elementos e precisa de uma verificação visual de alinhamento, margens e agrupamento. | Revisar a página no Power BI e agrupar visualizações relacionadas. |
| Contraste | Não foi possível confirmar todas as combinações de cores e estados de seleção apenas pela estrutura do arquivo. | Verificar legibilidade em títulos, rótulos, cartões e filtros; testar seleção e foco. |
| Proporção áurea | Não há evidência suficiente para afirmar que o layout atual siga essa proporção. | Usar apenas como referência de composição; priorizar clareza e leitura. |
| Segmentação de dados | Há um segmentador de data e visuais por categorias de negócio. | Confirmar o escopo dos filtros e os efeitos cruzados entre visuais. |
| Botões e menus de navegação | Há botões de ação no arquivo, mas o comportamento de cada um não foi testado. | Testar a navegação e criar menus consistentes nas três páginas. |
| Três páginas | O arquivo selecionado contém duas páginas. | Criar a página `Detalhamento` e conectar a navegação antes de considerar o requisito concluído. |
| Matriz de descrição de vendas | O documento da atividade lista uma aula específica para criar a matriz. | Inserir e formatar a matriz na página de detalhamento. |

## Limitação

O arquivo não foi aberto no Power BI Desktop neste ambiente Debian. Portanto, as alterações propostas são recomendações de implementação; não são alegações de alterações já feitas ou testadas.
