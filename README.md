# Análises de transações bancarias utilizando Pyspark
Esta análise é de cunho educacional para aprimorar minhas habilidades com pyspark abaixo esta listados os objetivos

### Objetivos
- Limpar e pré-processar os dados das transações PIX
- Analisar padrões de uso do PIX, tais como os canais mais utilizados e os valores de transação mais comuns
- Usar o PySpark MLlib para treinar e avaliar um modelo de detecção de fraude
- Avaliar o desempenho do modelo e fazer recomendações para melhorias futuras

### Dados
Os dados são um json provindo de simulação, e não de instituições bancarias verdadeiras.
O conjunto de dados inclui as seguintes informações para cada transação:
- Detalhes da transação: valor, tempo, remetente e receptor CPF/CNPJ, tipo
- Etiqueta de fraude: uma variável binária que indica se a transação foi fraudulenta (1) ou não (0)
