# Atividade 1

### 1. Explique, com suas palavras, o que é machine learning?
Machine Learning, em português **Aprendizado de Máquina**, é uma área da inteligência artificial que trabalho no desenvolvimento de algoritmos e modelos que permitem que os computadores "aprendam" a partir de dados. Em vez de serem explicitamente programados para realizar uma tarefa, os sistemas de machine learning usam dados para identificar padrões, fazer previsões ou tomar decisões. 

Existem diferentes tipos de aprendizado de máquina, incluindo:

- **Aprendizado Supervisionado:** O modelo aprende a partir de dados rotulados, onde a resposta correta é conhecida.
- **Aprendizado Não Supervisionado:** O modelo encontra padrões em dados não rotulados, sem respostas predefinidas.
- **Aprendizado por Reforço:** O modelo aprende por meio de tentativa e erro, recebendo recompensas por ações corretas.

Para que o aprendizado seja eficaz, é crucial utilizar dados válidos e de alta qualidade que contribuam para o objetivo desejado.

### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.
- **Conjunto de Treinamento:** É o conjunto de dados usado para "ensinar" o modelo. O algoritmo aprende os padrões e relações presentes nesses dados para fazer previsões ou classificações.

- **Conjunto de Validação:** É um conjunto separado usado para ajustar os hiperparâmetros do modelo e evitar overfitting (quando o modelo se ajusta demais aos dados de treinamento e perde a capacidade de generalizar). Ele ajuda a avaliar o desempenho do modelo durante o treinamento.

- **Conjunto de Teste:** É um conjunto de dados totalmente independente, usado para avaliar o desempenho final do modelo após o treinamento e a validação. Ele simula como o modelo se comportará com dados nunca vistos antes.  
  
Essa divisão é crucial para garantir que o modelo generalize bem e não apenas memorize os dados de treinamento.

### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.
Dados ausentes são comuns em conjuntos de dados e podem prejudicar o desempenho do modelo. Algumas abordagens podem ser tomadas nesses cenários: 
- **Remover linhas ou colunas:** Se a quantidade de dados ausentes for pequena, pode-se simplesmente excluir as linhas ou colunas afetadas.

- **Preencher com valores:** Substituir os valores ausentes por estatísticas como média, mediana ou moda (para dados numéricos) ou por um valor específico como "desconhecido" (para dados categóricos).

- **Usar algoritmos que lidam com dados ausentes:** Alguns algoritmos, como árvores de decisão, podem lidar diretamente com dados ausentes.

- **Imputação avançada:** Técnicas como k-Nearest Neighbors (k-NN) ou modelos preditivos podem ser usados para estimar valores ausentes com base em outros dados disponíveis.

### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?
Uma matriz de confusão é uma tabela que mostra o desempenho de um modelo de classificação. Ela compara as previsões do modelo com os valores reais, organizando os resultados em quatro categorias:

- **Verdadeiros Positivos (VP):** Casos em que o modelo previu corretamente a classe positiva.

- **Falsos Positivos (FP):** Casos em que o modelo previu a classe positiva, mas o valor real era negativo.

- **Verdadeiros Negativos (VN):** Casos em que o modelo previu corretamente a classe negativa.

- **Falsos Negativos (FN):** Casos em que o modelo previu a classe negativa, mas o valor real era positivo.

A matriz de confusão é usada para calcular métricas como acurácia, precisão, recall e F1-score, que ajudam a avaliar a qualidade do modelo.

### 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?
- **Construção Civil:** Previsão de falhas em estruturas - pode ser usado para prever falhas em estruturas como pontes, edifícios e estradas. Sensores coletam dados em tempo real sobre vibrações, tensões e outras métricas estruturais. Algoritmos de ML analisam esses dados para identificar padrões que indicam desgaste ou risco de colapso, permitindo manutenção preventiva e evitando acidentes.

- **Agricultura:** Monitoramento de safras - algoritmos de ML analisam dados de sensores, imagens de satélite e drones para monitorar o crescimento das plantas, a saúde do solo e as condições climáticas. Isso ajuda os agricultores a tomar decisões informadas sobre irrigação, fertilização e colheita, aumentando a produtividade e reduzindo custos.

- **Saúde:** Diagnóstico de doenças - algoritmos analisam imagens médicas (como raios-X e ressonâncias), sintomas relatados e dados de exames para identificar condições como câncer, doenças cardíacas e diabetes. Isso permite diagnósticos mais rápidos e precisos, melhorando os resultados para os pacientes.

- **Manufatura:** Controle de qualidade automatizado - na manufatura, algoritmos de ML são aplicados para inspecionar produtos em tempo real durante a produção. Usando visão computacional e análise de dados, eles detectam defeitos, como rachaduras, desalinhamentos ou imperfeições, garantindo que apenas produtos de alta qualidade cheguem ao mercado. Isso reduz desperdícios e aumenta a eficiência.





