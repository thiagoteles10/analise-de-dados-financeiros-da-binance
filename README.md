# analise-de-dados-financeiros-da-binance

O conjunto de dados fornecido contém informações sobre transações financeiras da corretora de criptomoedas Binance em uma variedade de operações. Cada registro no conjunto de dados representa uma operação específica em uma determinada Criptomoeda. Os atributos presentes nos dados incluem:

UTC_Time: indica a data e a hora em que a operação ocorreu, registrado no formato UTC (Tempo Universal Coordenado).
Account: representa o tipo de conta associada à operação.
Operation: descreve a natureza da operação, que pode incluir depósitos, gastos, compras de moeda, taxas, transferências, entre outros.

Coin: indica a moeda envolvida na operação, como BRL (Real Brasileiro),ADA (Cardano), LINK, ROSE, DOT, MATIC, UNISWAP E ACALA.
Change: representa o valor da alteração financeira ocorrida na operação. As operações registradas incluem depósitos, transações de gasto, compras de moeda, taxas, transferências entre contas, realização de lucros e perdas, taxas de financiamento, compensação de fundos de seguro, distribuição de vouchers de dinheiro, compra e recompensas de staking, distribuição de ganhos, resgates de ganhos, saques, entre outros.

Change: representa o valor da alteração financeira ocorrida em cada operação. Esse valor pode ser positivo ou negativo, dependendo do tipo de operação registrado.

Para operações como "Deposit" (depósito) e "Transaction Buy" (compra de moeda), o valor em "Change" será positivo, indicando um aumento no saldo ou um valor adicionado à conta.
Já para operações como "Transaction Spend" (gasto), "Fee" (taxa) e outras operações de redução de saldo, o valor em "Change" será negativo, indicando uma diminuição no saldo ou um valor retirado da conta.
O valor em "Change" está associado à moeda específica registrada na coluna "Coin". Por exemplo, se a moeda for BRL (Real Brasileiro), o valor em "Change" representará uma quantia em reais.

Essa coluna é fundamental para compreender o impacto financeiro de cada operação e calcular totais, saldos ou análises adicionais com base nas alterações ocorridas em cada transação.

Com base nesses atributos, o conjunto de dados permite analisar a atividade financeira em diversas criptomoedas. É possível explorar os padrões de depósitos, gastos e outras operações ao longo do tempo, além de investigar a distribuição de valores.

 A análise desses dados pode fornecer insights valiosos sobre os diferentes tipos de transações financeiras realizadas na conta.
