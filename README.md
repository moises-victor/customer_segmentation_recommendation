## Projeto de Segmentação e Recomendação de Clientes

Em um cenário de negócios cada vez mais competitivo, compreender e atender às necessidades dos clientes de forma personalizada é um diferencial crucial para o sucesso. Este projeto surge como uma estratégia que combina análise de dados avançada e inteligência artificial para aprimorar o relacionamento com os clientes e impulsionar as vendas.

### Importância da Segmentação de Clientes
A segmentação de clientes é o processo de dividir uma base de clientes em grupos distintos com características e comportamentos semelhantes. Permite uma compreensão mais clara dos clientes, idnetificando padrões dentro de cada segmento, facilitando o desenvolvimento de estratégias de marketing.

### Benefícios das Recomendações Personalizadas
A recomendação de produtos baseia-se em algoritmos que analisam o comportamento de compra e as preferências dos clientes, potencializando o aumento das vendas, fidelização dos clientes e melhoria da exepriência do usuário

### Objetivos
O principal objetivo aqui é ampliar a eficiência das estratégias de marketing e impulsionar as vendas por meio da segmentação de clientes utilizando o algoritmo de aprendizado de máquina [K-Means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html). No final será criado um algoritmo de recomendação de produtos ainda não adquiridos pelo cliente com base em seu cluster.

### Sobre os dados
Os dados disponíveis no [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail) são de um varejista do Reino Unido e contempla todas as transações realizadas entre 2010 e 2011. 

Descrição do dataset:

Variável - Descrição
- InvoiceNo - Código representando cada transação. Se o código começa com a letra 'c', quer dizer que a compra foi cancelada.
- StockCode - Código que identifica cada produto.
- Description - Descrição de cada produto.
- Quantity - O número de produtos adquiridos em cada transação.
- InvoiceDate - Data e hora em que a transação foi realizada.
- UnitPrice - Preço unitário do produto na transação.
- CustomerID - Identificador único pra cada cliente.
- Country - O país do cliente.
