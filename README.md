# Prophet - Previsão de Séries Temporais para Negócios

Este repositório contém um exemplo de utilização da biblioteca Prophet para previsão de séries temporais voltadas para negócios. Prophet é uma ferramenta desenvolvida pelo Facebook Research com o objetivo de facilitar a previsão de séries temporais, especialmente para usuários com pouco conhecimento em modelagem estatística.

## Problemas Abordados

Prophet foi projetado para enfrentar as seguintes dificuldades comuns encontradas em muitas séries temporais de negócios:

- Efeitos sazonais causados pelo comportamento humano, como ciclos semanais, mensais e anuais, e variações nos feriados.
- Mudanças na tendência devido a novos produtos e eventos de mercado, bem como a presença de outliers.
- Acessibilidade para um amplo público de analistas, incluindo aqueles com pouco conhecimento em séries temporais.
- Aplicabilidade a uma ampla gama de problemas de previsão distintos.
- Estimação automatizada do desempenho de um grande número de previsões, incluindo a sinalização de potenciais problemas para inspeção subsequente pelo analista.

## Como o Prophet Funciona

O Prophet utiliza um modelo de regressão aditiva, composto por três componentes principais:

- Tendência não periódica.
- Sazonalidade, que captura mudanças periódicas.
- Componente de feriados, que contribui com informações sobre feriados e eventos.

## Conjunto de Dados

O exemplo neste repositório utiliza dados sobre a produção de veículos automotores no país, refletindo o desempenho das vendas das empresas associadas, incluindo informações sobre estoque, venda e produção de veículos e motociclos.

## Como Usar o Código

O código fornecido neste repositório demonstra como usar o Prophet para prever séries temporais. Ele inclui as seguintes etapas:

1. Importação de bibliotecas e montagem do Google Drive (este passo é específico para ambiente Colab).
2. Leitura e pré-processamento dos dados.
3. Visualização dos dados.
4. Divisão do conjunto de dados em treino e teste.
5. Criação e ajuste do modelo Prophet.
6. Previsão usando o modelo ajustado.
7. Avaliação da performance do modelo.
8. Visualização dos resultados da previsão e decomposição de componentes.

## Resultados e Avaliação

Os resultados da previsão são avaliados usando duas métricas principais: Raiz Quadrada do Erro Quadrático Médio (RMSE) e Erro Médio Absoluto (MAE). Além disso, é possível explorar outras métricas e técnicas de validação cruzada para aprimorar o desempenho do modelo.

Esperamos que este exemplo seja útil para aqueles que desejam aplicar o Prophet em problemas de previsão de séries temporais para negócios. Sinta-se à vontade para explorar, modificar e adaptar o código conforme necessário para atender às suas necessidades específicas.
