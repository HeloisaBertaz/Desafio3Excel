# Desafio3Excel


Este repositório contém a entrega do desafio de análise de dados e construção de um Dashboard de Vendas no Excel, focado no desempenho de assinaturas e add-ons do Xbox Game Pass. O objetivo do projeto foi organizar dados brutos de assinantes e transformá-los em um painel interativo para suporte à tomada de decisão de negócios.

Durante o desenvolvimento na aba Cálculos, foram estruturadas tabelas dinâmicas para responder às principais questões operacionais e comerciais:

1. Faturamento Total de Planos Anuais:
   Análise do faturamento agregado gerado por assinaturas de ciclo anual.

2. Faturamento por Renovação Automática (Auto Renewal):
   Comparativo de faturamento entre clientes com renovação automática ativa (Yes) e inativa (No).

3. Desempenho de Vendas do EA Play Season Pass:
   Volume e receita gerados pelo passe de temporada EA Play entre as categorias de planos (*Core*, *Standard* e *Ultimate*).

4. Desempenho de Vendas do Minecraft Season Pass:
   Totalização das vendas de passes do Minecraft por tipo de plano.

A planilha foi organizada de forma modular para garantir boas práticas de modelagem de dados:

- `Bases`: Tabela contendo a base bruta de assinantes (ID, nome, plano, tipo de assinatura, cupons e adicionais).
- `Cálculos`: Área técnica contendo as Tabela Dinâmicas e fórmulas de apoio (`SOMA`, `MÉDIA`, `OBTERDADOSDINAMICOS`).
- `Dashboard`: Painel visual com cards de métricas principais (KPIs), gráficos explicativos e filtros dinâmicos de segmentação por tipo de assinatura.
- `Assets`: Identidade visual com a paleta oficial de cores da marca Xbox (tons verdes `#22C55E` e `#9BC848`).
