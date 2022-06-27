# Análise de Dados com Machine Learning
 
Uma verdadeira análise de dados não esta completa se não conta com uma análise preditiva. Machine Learning fornece as ferramentas para poder fazer uma verdadera análise, isto é, mediante técnicas de aprendizado de máquina podemos ciar algoritmos (aplicações) para poder estabelecer soluções diretas a problemas reais numa empresa ou instituição. 

---
---


Antes de começar vou compartir algumas das aulas que ministrei na pós de engenharia na FMU na disciplina de Análise Multivariada e Séries Temporais.

**Básico**:

1. Análise de Regressão Linear: A primeira aula esta focalizada nos conceitos básico de uma análise de regressão linear (método de mínimos quadrados, algebra matricial, etc). Os cálculos foram feitos usando ferramentas básicas como **Excel** e o software **R**, posteriormente se faz uma comparação com o programa **SPSS**.
    1. Com Python:
       1. Classificacao.ipynb -> uso do modelo de K-NN para fazer clasificação de elementos.
    1. Com R:
       1. ajuste linear.R -> gráfico de dispersão de dados de excel fazendo um ajuste linear.
           1. dados: alunos.xlsx
       1. ajuste linear nomalidade.R -> gráfico de dispersão de dados em arquivos .txt fazendo ajuste e teste de normalidade.
           1. dados: dados1.txt
       1. ajuste linear e estatistica -> gráfico de dispersão de dados em arquivos .txt fazendo ajuste um teste estatístico.
           1. dados: dados1.txt
       1. matriz de correlacao -> primeiro gráfico da correlação entre varias variáveis quantitativas e categóricas.
           1. dados: ind_sicio_econ.xlsx
    1. Com Excel: 
        1. Exemplo 6tab.xlsx -> Regressão Linear Múltipla (feito na aula: Análise de Regressão) relacionada com quantidade vendida de um produto em função do preço e do investimento feito.
    1. Com SPSS:
1. Componentes Principais: Aula focalizada nos principios da análise de componentes principais .Os cálculos foram feitos usando ferramentas como o programa **SPSS** e se faz uma comparação com o software **R**

    
---
---

**Casos:**

Aquí são apresentados os casos que foram estudados, separados em pastas diferentes:

1. **Custos Médicos:** Calcula-se os custos médicos do plano de saúde para uma pessoa baseado em caraterísticas como Idade, Índice de massa corporal, Sexo, se é fumante ou não, etc. 
    1. Custos Médicos RLinear: Este é o primeiro e mais simple de todos, pois fue feito usando só técnicas **Regressão Linear** e considerando só duas das variáveis uma numérica (índice de massa corporal) e uma outra categórica (fumante). Posteriormente será feito com mais variáveis e com outras técnicas mais apropriadas para o estudo de variáveis categóricas como o **modelo-KNN**, etc.  
    2. Custos Médicos K-NN: Se estabelece uma comparação entre o cálculo anterior (**Regressão Linear**) e o **modelo-KNN** (usado como regressão e não como classificador)
    3. Custos Médicos Arvores Decisao: Se estabelece uma comparação entre os cálculos anteriores (**Regressão Linear**), o **modelo-KNN** (usado como regressão e não como classificador) e o modelo de **Árvores de Decisão** (usado como regressão)
    4. Custos Médicos RLinear Multipla: Melhora feita, usando mais variáveis independientes, foi incluída a variável **Idade**.
    5. Custos Médicos Modelos +Variaveis: Se estabelece uma comparação entre os cálculos de todos os modelos, com a inclusão da variável **Idade**.
    6. Custos Médicos combinacao Modelos: Se estabelece uma combinaçãao entre os modelos (**Regressão Linearr**), o **modelo-KNN** (usado como regressor) e o modelo de **Árvores de Decisão** (usado como regressor)
    7. Custos Médicos combinacao Modelos +Variaveis: Se estabelece uma combinaçãao entre os modelos (**Regressão Linearr**), o **modelo-KNN** (usado como regressor) e o modelo de **Árvores de Decisão** (usado como regressor) com a inclusão de mais uma variável, **Idade**.

1. **Classificação Fumante Modelos (Custos Médicos):** Mostra-se a técnica classificação usando os modelos **Regressão Logística**, **K-NN** e **Árvores de Decisão** e considerando caraterísticas como Idade, Índice de massa corporal, Sexo, custo, etc
    1. Classificacao Fumante RLogistica: Foi feita uma Regressão logística para a classificação (Fumante ou Não) considerando uma função linear para a região de separação das clases. 
    2. Classificação Fumante Modelos (Custos Médicos): Compara-se a técnica classificação de uma variável categórica (Fumante) usando os modelos **Regressão Logística**, **K-NN** e **Árvores de Decisão**.
    3. Classificação Fumante Modelos +Variaveis (Custos Médicos): Compara-se a técnica classificação de uma variável categórica (Fumante) usando os modelos **Regressão Logística**, **K-NN** e **Árvores de Decisão** e com a inclusão da variável **Idade**.
    4. Classificação Fumante Combinacao Modelos: (Custos Médicos):Se estabelece uma combinaçãao entre os modelos (**Regressão Logísticar**), o **modelo-KNN** (usado como classificador) e o modelo de **Árvores de Decisão** (usado como classificador)
    5. Classificação Fumante Combinacao Modelos +Variaveis: (Custos Médicos):Se estabelece uma combinação entre os modelos (**Regressão Logística**), o **modelo-KNN** (usado como classificador) e o modelo de **Árvores de Decisão** (usado como classificador) com a inclusão da variável **Idade**.
    6. Classificação Fumante Baggins e R_Forest: Mostra-se a técnica de Baggins e de Random Forest na clasificação da variável **Fumante**.  
    7. Classificação Fumante Baggins e R_Forest +Variaveis: Mostra-se a técnica de Baggins e de Random Forest na clasificação da variável **Fumante** com a inclusão da variável **Idade**.
    
1. **Classificação de Flores (Iris):** Mostra-se a técnica classificação usando o **modelo de K-NN**
    1. Tipo de Flores KNN:
    2. ? 
1. **Churn:**  Calcula-se a possibilidade de um cliente desistir de um serviço ou de um produto baseado no histórico de todo um conjunto de elementos. 
    1. Churn: Para este caso temos que determinar (clasificação de clientes) se os clientes vao entrar em **Churn** considerando uma base de dados com muitas caraterísticas (variáveis). Foram utilizados diferentes modelos de Machine Learning (**Regressão Logística**, **K-NN**, **Árvores de Decisão**, **Baggins** e **Random Forest**) 
    2. Fraude:
1. **Sobrevivientes:** (Caso do TITANIC - Competição no site do Kaggle) A ideia é determinar se con os dados que se tem dos passageiros (891 dados: com diferentes características, em total 12) determinar se um determinado passageiro sobreviviu ou não.

3. **Não Supervisonados**
    1. K-Mean
    2. PCA 
    
