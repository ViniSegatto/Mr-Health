# Análise e Modelagem para a empresa Mr-Health
![image](https://github.com/ViniSegatto/Mr-Health/assets/117327390/27271eb5-2474-4aaf-b21b-1d476035c468)

## 1. Descrição e objetivos
  * Este é um projeto de ciência de dados desde a coleta de dados até a modelagem em que é realizada a limpeza, análise exploratória e modelagem dos dados
  * A solução foi planejada com base no framework CRISP-DM, envolvendo o entendimento do problema, entendimento dos dados, limpeza dos dados, análise dos dados, modelagem.
  * A limpeza foi fundamental, dado que os três conjuntos originais estavam separados.
  * A análise e modelagem se dividem em duas abordagens:
  * Análise e modelagem de desempenho: O objetivo dessa análise consiste em identificar as principais variáveis que impactam no controle de estoque, como elas se relacionam dele e como elas podem ser utilizadas para a predição desse estoque.
  * Foi utilizado o modelo XGBoost, dado o alto poder preditivo, rapidez de treinamento e predição, e flexibilidade no pré-processamento.
  * Tais analises servem para que João possa realizar o se concentrar na análise destas informações e na tomada de ações junto aos fornecedores e gestores das unidades.
  * O modelo desenvolvido pode ajudar João a suprir o estoque com a quantidade adequada de Itens, para que não haja nem desperdicio nem falte itens para os clientes, mesmo com as mudanças sazonais que podem acontecer.

  ## 2. Limpeza de dados
   *   A limpeza foi fundamental, dado que o conjunto original estava separado em 3 arquivos diferentes. tornando a manipulação, análise e modelagem dos dados inviável. Nessa etapa, foram realizadas as seguintes tarefas:
   *  Entendimento dos dados de cada planilha.
   *  Entendimento dos dados em uma planilha unificada.
   *  Analisamos dados duplicados, unicos, tipos de dados, quantidade de dados e muito mais com a função dfSummary() que nos ajuda a poupar tempo e linhas de codigo.

## 3. Análise de desempenho
 *   O objetivo dessa análise consiste em identificar as principais variáveis que podem impactar nosso controle de estoque, como elas se relacionam com o desempenho dele e como podem ser utilizadas para a predição desse modelo. 
  *   Perguntas respondidas na Análise:
  *  Quais os itens mais vendidos.
  *  Qual a quantidade de itens mais vendidos.
  *  Qual a maior parcela do valor total, minima e maxima. 
  * Tendência de vendas diarias com regressão.

## 3.1 Principais insights

![image](https://github.com/ViniSegatto/Mr-Health/assets/117327390/feffb4ee-0459-4e8f-af82-274810835877)
  * A tendência de vendas registra uma linha de regressão que tem uma inclinação positiva, indicando que as vendas diárias tendem a aumentar com o tempo. 
![image](https://github.com/ViniSegatto/Mr-Health/assets/117327390/53235a19-8c1c-4613-b6f8-45bd95b924b4)
  * A variância entre os itens é baixa. Isso significa que a quantidade vendida de cada item se mantém relativamente constante ao longo do tempo, sem grandes flutuações.
    
![image](https://github.com/ViniSegatto/Mr-Health/assets/117327390/f69683d1-0d3f-4d04-9f56-a234eafadcf6)
![image](https://github.com/ViniSegatto/Mr-Health/assets/117327390/0ccce167-a0aa-44f2-8814-3e132aa13ab6)

  * Há poucos valores extremos. A quantidade de Itens pedidos e de Valor total tem uma variancia relativamente curta.

## 4. Modelagem. 


