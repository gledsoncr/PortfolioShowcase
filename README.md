# PortfolioShowcase
 
Este repositório existe principalmente para visualização de projetos que mantenho em modo privado, principalmente aqueles com foco em tomadas de descisões para investimentos financeiros.

## Análise de Dados Financeiros com Python: Backtests para Estratégias de Negociação

### Comparação entre Estratégias de Seleção de Ativos para Negociação
![Relatório de Métodos de Seleção de Ativos](/screenshots/asset_analysis_multi_report_04.png?raw=true "Relatório de Métodos de Seleção de Ativos")
- Eixo horizontal (Selection method) apresenta os diversos métodos de seleção de ativos, sendo cada método um algorítmo único com regras específicas para selecionar ativos.
- Pontos Verdes representam a performance (Cumulative Change %) de estratégias testadas em alguns ativos do IBOV.
- Pontos Vermelhos representam a performance (Cumulative Change %) de estratégias testadas em alguns ativos do SPX100.
- Pontos Amarelos representam a performance (Cumulative Change %) de estratégias testadas em alguns Criptoativos.

### Performance de Diversas Estratégias de Negociação durante o mesmo Período separadas por Grupos
![Relatório de Grupos de Ativos](/screenshots/asset_analysis_multi_report_01.png?raw=true "Relatório de Grupos de Ativos")
- Pontos Verdes representam a performance (Cumulative Change %) de estratégias testadas em alguns ativos do IBOV.
- Pontos Vermelhos representam a performance (Cumulative Change %) de estratégias testadas em alguns ativos do SPX100.
- Pontos Amarelos representam a performance (Cumulative Change %) de estratégias testadas em alguns Criptoativos.

### Variações Mínimas (Drawdown) de Diversas Estratégias de Negociação durante o mesmo Período
![Relatório de Variações Mínimas de Ativos](/screenshots/asset_analysis_multi_report_03.png?raw=true "Relatório de Variações Mínimas de Ativos")
- Pontos Verdes representam a performance (Minimum Change %) de estratégias testadas em alguns ativos do IBOV.
- Pontos Vermelhos representam a performance (Minimum Change %) de estratégias testadas em alguns ativos do SPX100.
- Pontos Amarelos representam a performance (Minimum Change %) de estratégias testadas em alguns Criptoativos.

### Relatório de Performance para Ativos selecionados via algorítmo a partir da cesta de ativos do IBOV
Principais empresas do Brasil listadas em mercado de ações.
![Relatório de Performance IBOV](/screenshots/asset_analysis_ibov.png?raw=true "Relatório de Performance IBOV")
- Eixo vertical (Last close change %) representa a retabilidade de cada investimento ao final do período.
- Eixo horizontal representa o período.
- Pontos Cinza no relatório representam a performance dos ativos do IBOV.
- Pontos Amarelos representam a performance dos ativos selecionados através do algorítmo.
- Linha cor Mostarda (Cumulative %) representa a performance acumulada da estratégia.
- Linha Preta (Compound:1%), representando um índice de referência que produz um ganho composto de 1% ao mês.

### Relatório de Performance para Ativos selecionados via algorítmo a partir da cesta de ativos do S&P100
Cem maiores empresas dos Estados Unidos listadas no mercado de ações.
![Relatório de Performance S&P100](/screenshots/asset_analysis_spx100.png?raw=true "Relatório de Performance S&P100")
- A descrição do gráfico é semelhante ao anterior.
- Pontos Cinza no relatório representam a performance dos ativos do SPX100.
- Destaque para a performance, linha cor Mostarda (Cumulative %), que por se tratar de um mercado mais maduro e resiliente, observou resultados superiores ao IBOV.

### Relatório de Performance para Criptoativos selecionados via algorítmo a partir de uma cesta com os maiores Criptoativos por Captalização de Mercado
![Relatório de Performance Cripto](/screenshots/asset_analysis_crypto.png?raw=true "Relatório de Performance Cripto")
- A descrição do gráfico é semelhante aos anteriores.
- Pontos Cinza no relatório representam a performance dos ativos do Criptoativos.
- Desta vez a performance, linha cor Mostarda (Cumulative %), foi superior ao IBOV, mas inferior ao S&P100, por se tratarem de ativos com altíssima volatilidade no período.

## Estratégias em PineScripts: Análise de Dados e Backtests para ativos Financeiros
### Backtest para Estratégias de Investimentos baseado em Sinais Lógicos para Auxilio na Tomada de Decisão
![Backtest para Estratégias de Investimentos](/screenshots/pine_script.png?raw=true "Backtest para Estratégias de Investimentos")
- Marcações "Long" indicam sinais favoráveis para compra do ativo.
- Marcações "Close" indicam sinais favoráveis para venda do ativo comprado.
- As linhas coloridas são uma indicação visual dos parâmetros utilizados para gerar os sinais.

### Telas de Configuração para Customização do Algorítmo
![Telas de Configuração](/screenshots/pine_script_config.png?raw=true "Telas de Configuração")
- É possível customizar alguns testes e comparar com diversas configurações diferentes.

