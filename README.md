# ANÁLISE DA PREVISÃO DE DEMANDA DA PRODUÇÃO DE GÁS NATURAL NO ESTADO DA BAHIA UTILIZANDO MÉTODOS ESTATÍSTICOS DE MODELOS AUTORREGRESSIVOS

Este repositório foi criado como parte do Trabalho de Conclusão de Curso (TCC) em Engenharia de Produção na Universidade Federal da Bahia (UFBA). Ele contém o código em R e os dados utilizados para a análise da produção de gás natural na Bahia entre 2000 e 2022.

## Descrição
O objetivo deste projeto é aplicar modelos de séries temporais, como ARIMA, ETS e Regressão Linear, para prever a produção futura de gás natural. A análise considera dados históricos mensais fornecidos gratuitamente no site da ANP ([producao-gas-natural-m3.xls (live.com)](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fwww.gov.br%2Fanp%2Fpt-br%2Fcentrais-de-conteudo%2Fdados-estatisticos%2Fde%2Fppg%2Fproducao-gas-natural-m3.xls&wdOrigin=BROWSELINK)). No meu caso, utilizei os dados de produção de gás natural no estado da Bahia entre os anos de 2000 a 2022.


## Instalação

## Como Usar

1. Clone este repositório:
   
   git clone https://github.com/Ess8504/S-ries-Temporais.git

2. Certifique-se de que você tem o R e as bibliotecas necessárias instaladas.
- Lista de pacotes: `forecast`, `ggplot2`, `readxl`, `dplyr`, `tidyr`, `lubridate`, `neuralnet`, `tidyverse`.

## Como Usar

1. Abra o arquivo `analise_series_temporais.R` no RStudio.
2. Execute o código para gerar as análises e os gráficos.
3. Os dados estão disponíveis na planilha `producao_gas_natural_m3.xlsx`.

## Exemplo de Execução
Aqui está um exemplo de como rodar o código no RStudio para gerar a análise:

# Carregue os pacotes
lapply(pacotes, library, character.only = TRUE)

# Carregue os dados
dados <- read_xlsx("producao_gas_natural_m3.xlsx")

# Execute as análises conforme descrito no código R
Isso vai gerar gráficos de análise exploratória, decomposição da série temporal, previsões usando modelos ARIMA, ETS, e Regressão Linear, entre outros.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes. 
