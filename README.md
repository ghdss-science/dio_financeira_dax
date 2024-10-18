## Dio Financeira 

Esse projeto foi desenvolvido com o objetivo de analisar dados financeiros de uma planilha pública obtida de um site americano, com ênfase em colunas chave. O trabalho envolveu várias etapas, 
desde a preparação dos dados até a execução de estratégias analíticas básicas. 
O foco principal foi estabelecer uma relação clara e consistente com os dados, conduzindo a análises que forneceram insights valiosos. 
Esses insights apoiaram a tomada de decisões financeiras mais eficazes, permitindo avaliar o desempenho de diferentes países, segmentos de mercado e períodos ao longo dos anos.

```bash

  id = Identificador único de cada registro da planilha. Serve para garantir que cada linha seja distinguida individualmente.
  Segment = Refere-se ao setor ou categoria de negócios em que as vendas estão ocorrendo . 
  Country = Representa o país onde as vendas foram realizadas.
  Product = Nome ou tipo do produto vendido.
  Discount_Band = Faixa de desconto aplicada ao produto, por exemplo, "10%", "20%", etc.
  Units_Sold = Quantidade de unidades do produto que foram vendidas.
  Manufacturing_Price = Preço de fabricação ou custo unitário do produto para a empresa.
  Sale_Price = Preço de venda do produto ao consumidor.
  Gross_Sales = Vendas brutas, que é o valor total das vendas antes dos descontos. Geralmente é calculado como Units_Sold * Sale_Price.
  Discounts = Valor total de descontos concedidos, que pode ser calculado com base na faixa de desconto aplicada.
  Sales = Vendas líquidas, ou seja, o valor de vendas após a aplicação dos descontos. Calculado como Gross_Sales - Discounts.
  COGS = Custo dos bens vendidos, ou seja, o custo direto envolvido na produção dos produtos vendidos, como matéria-prima e mão de obra.
  Profit = Lucro gerado pela venda, calculado como Sales - COGS. Representa o ganho financeiro após todos os custos de produção.
  Date =  Data exata da venda.
  Month_Number = Número correspondente ao mês da venda (1 para janeiro, 2 para fevereiro, etc.).
  Month Name = Nome do mês da venda, como "Janeiro", "Fevereiro", etc.
  Year = Ano em que a venda foi realizada.

```
Esse processo gerou resultados robustos, que contribuíram diretamente para uma melhor compreensão do cenário financeiro global e forneceram subsídios para decisões estratégicas baseadas em dados confiáveis.

## Conhecimentos Adquiridos nesse projeto 

Fui transparente em relação aos métodos e algoritmos utilizados para explicar e realizar a coleta de dados na linguagem Python, abordando de forma clara todas as dinâmicas 
e deduções necessárias para responder corretamente às questões da planilha dio_financeira. 
Além disso, destaquei as justificativas de cada decisão tomada com base nos dados, assegurando que o processo fosse claro e embasado por insights precisos.

Na criação de dashboards no Power BI, utilizei slicers e gráficos dinâmicos para construir interfaces interativas e responsivas. 
A reutilização de componentes foi maximizada através da segmentação de medidas e colunas calculadas, promovendo maior eficiência e clareza no desenvolvimento dos relatórios e análises.

Foi realizada uma especificação cuidadosa na importação de bibliotecas e pacotes essenciais, especialmente para operações envolvendo cálculos e manipulação de dados. Essa abordagem garante que o projeto seja modular e flexível, 
seguindo as melhores práticas de desenvolvimento em Python. Ao estruturar as funções e métodos de forma clara e eficiente, o código se mantém organizado, permitindo fácil manutenção e escalabilidade.

## Dificuldades adquiridos nesse projeto 

A integração entre as camadas de dados tem sido um desafio constante. Otimizar a comunicação entre os modelos, as visualizações e os controladores de processamento, principalmente em um cenário com tantas variáveis e complexidade,
como a planilha financeira da dio que não foi uma tarefa simples. A dificuldade de garantir que os dados fluam de maneira eficiente e sem interrupções tornou o processo mais demorado e desgastante do que o esperado. 
Cada etapa exige um cuidado meticuloso para evitar que pequenas falhas se transformem em grandes problemas, o que muitas vezes resultou em retrabalho.

Além disso, o design das visualizações trouxe sua própria série de dificuldades. Encontrar uma forma de organizar e centralizar os elementos, de modo a evitar sobrecarga de informações e manter a clareza dos insights, foi um processo cheio de tentativas e erros. 
Houve momentos em que parecia impossível alinhar todas as peças e alcançar uma experiência de análise fluida e consistente. 
A sensação de lentidão no progresso e a frustração com resultados que não atendiam às expectativas tornaram o processo ainda mais desafiador, exigindo perseverança e constante reajuste das abordagens.

## Tecnologias Utilizadas 

-[Anaconda](https://anaconda.org/) 

-[Python](https://www.python.org/) 

-[Pandas](https://pandas.pydata.org/) 

-[Power BI](https://www.microsoft.com/pt-br/power-platform/products/power-bi) 

-[sqlite 3](https://pandas.pydata.org/) 

## Baixar e visualizar o Projeto via Python

```bash

  # fazer um git clone do projeto pelo terminal ou baixar e obter via winrar

  # Obter Python, Anaconda, Jupyter notebook ou outra Ide instalado na sua maquina

  # acessar o terminal no seu sistema operacional e escrever jupyter notebook para ver a análise de dados no python pandas
    ou obter o Vs code e instalar a extensão do python e jupyter notebook para ver no pandas 
```

## Baixar e visualizar o Projeto via Power BI 

```bash

   # fazer um git clone do projeto pelo terminal ou baixar e obter via winrar

   # Obter o Power BI instalado na sua maquina e ver via desktop ou possuir uma conta corporativa para ver ma web. 

```

## Visualização do Projeto - Power BI 
