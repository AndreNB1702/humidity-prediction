Descrição
Este projeto utiliza o modelo SARIMA, um modelo de séries temporais que considera padrões sazonais, para prever a umidade relativa do ar na cidade de Porto Velho, Rondônia. Os dados foram obtidos do INMET.

Etapas realizadas
Importação dos arquivos de dados.
Limpeza dos dados: remoção de colunas irrelevantes e preenchimento de valores faltantes utilizando interpolação temporal.​
Treinamento do modelo SARIMA com diferentes combinações de parâmetros.
Visualização dos resultados com gráficos comparando valores reais e previstos.

Objetivo
Demonstrar a aplicação do modelo SARIMA em dados reais de séries temporais e avaliar seu desempenho na previsão de umidade em Porto Velho.

Resultado
O modelo final escolhido foi o modelo 2, que possui os parâmetros (1, 1, 1), (1, 1, 1, 12).
