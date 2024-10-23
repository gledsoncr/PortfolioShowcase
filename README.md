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

## Projeção de Cenários Financeiros com Simulação de Monte Carlo para Gestão de Riscos e Planejamento Estratégico
![Projeção de Cenários Financeiros com Simulação de Monte Carlo para Gestão de Riscos e Planejamento Estratégico](/screenshots/monte_carlo.png?raw=true "Projeção de Cenários Financeiros com Simulação de Monte Carlo para Gestão de Riscos e Planejamento Estratégico")
- Simulação gerada através de algorítmo em Python para apresentar diversas possibilidades de projeções de cenários de um ativo.
- A projeção leva em consideração as variações do ativo em um determinado período para gerar a simulação.
- Este gráfico está apresentando um total de 1000 simulação, condensadas visualmente para facilitar o entendimento.
- A linha Azul (close.real) representa o preço real do ativo e demonstra como este se comportou ao longo do tempo.
- A linha Verde (max) representa os valores máximos das simulações.
- A linha Vermelha (min) representa os valores mínimos das simulações.
- Utilizado para identificar padrões, agrupamentos e contextos principais em um conjunto de palavras-chave para SEO.

## Visualizando Conexões com Gráfico Network
![Gráfico Network](/screenshots/WordCounter.png?raw=true "Gráfico Network")
- Gerado através de um algorítmo em Python para apresentar as conexões entre palavras repetidas em um conjunto de dados.
- Utilizado para identificar padrões, agrupamentos e contextos principais em um conjunto de palavras-chave para SEO.
- Este algorítmo possui código aberto e pode ser acessado através do link: [https://github.com/gledsoncr/WordCounter](https://github.com/gledsoncr/WordCounter "WordCounter - Visualizando Conexões com Gráfico Network")

## Scatter Plot para Identificação de Melhores Oportunidades de Vendas
![Scatter Plot](/screenshots/HtmlToDataFrame.png?raw=true "Scatter Plot")
- Gerado através de um algorítmo em Python que é capaz de ler um código HTML copiado de um website de produtos ou loja virtual, localizar marcações específicas para identificar os produtos dentro do código, criar um DataFrame (tabela de dados) com as informações relevantes de cada produto e ao final gerar um gráfico para analisar os dados de forma visual e intuitiva.
- Cada ponto no gráfico representa um produto para venda.
- O eixo vertical (Commission) representa o valor de comissão recebida por cada venda de produto, quanto maior, mais vantajoso para o vendedor.
- O eixo horizontal (Max Price) representa o preço máximo de cada produto, o que pode indicar um aumento na dificuldade de vendas para produtos mais caros.
- A coloração (Temperature) dos pontos indica o quão bem cada produto vem sendo vendido, sendo os tons claros Piores e os tons avermelhados Melhores.
- Os simbolos indicados na parte superior direita do gráfico (comment rating) apresentam uma indicação visual para o ranking de avaliação de cada produto, indo de 1 (pior) até 5 (melhor).
- O tamanho de cada ponto indica a quantidade de avaliações, tamanhos maiores indicam mais avaliações.
- As linhas são a indicação visual da Regressão Linear para cada simbolo.
- Este algorítmo possui código aberto e pode ser acessado através do link: [https://github.com/gledsoncr/HtmlToDataFrame](https://github.com/gledsoncr/HtmlToDataFrame "HtmlToDataFrame - Scatter Plot para Identificação de Melhores Oportunidades de Vendas")

## Planilha para Simulação de Dados para Folha de Apontamento de Horas
![Planilha para Simulação de Dados para Folha de Apontamento de Horas](/screenshots/EmployeeRecordSheetSimulator.png?raw=true "Planilha para Simulação de Dados para Folha de Apontamento de Horas")
- Planilha criada em Excel para simular dados em uma folha de apontamento de horas.
- Permite customização para que o algorítmo procedural gere os dados da maneira desejada.
- Esta planilha possui código aberto e pode ser acessada através do link: [https://github.com/gledsoncr/EmployeeRecordSheetSimulator](https://github.com/gledsoncr/EmployeeRecordSheetSimulator "EmployeeRecordSheetSimulator - Planilha para Simulação de Dados para Folha de Apontamento de Horas")
