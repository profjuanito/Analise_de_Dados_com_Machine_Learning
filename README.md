# Análise de Dados com Machine Learning
 
Uma verdadeira análise de dados não esta completa se não conta com uma análise preditiva. Machine Learning fornece as ferramentas para poder fazer uma verdadera análise, isto é, mediante técnicas de aprendizado de máquina podemos ciar algoritmos (aplicações) para poder estabelecer soluçõess diretas a problemas reais numa empresa ou instituição. 

Antes de começar vou compartir algumas das aulas que ministrei na pós de engenharia na FMU na disciplina de Análise Multivariada e Séries Temporais.

Básico:

1. Análise de Regressão Linear: A primeira aula esta focalizada nos conceitos básico de uma análise de regressão linear (método de mínimos quadrados, algebra matricial, etc). Os cálculos foram feitos usando ferramentas básicas como **Excel** e o software **R**, posteriormente se faz uma comparação com o programa **SPSS**.
    1. Com Python:
       1. Clasificacao.ipynb -> modelo de K-NN de clasificação  
    1. Com R:
       1. ajuste linear.R -> gráfico de dispersão de dados de excel fazendo um ajuste linear.
           1. dados: alunos.xlsx
       1. ajuste linear nomalidade.R -> gráfico de dispersão de dados em arquivos .txt fazendo ajuste e teste de normalidade.
           1. dados: dados1.txt
       1. ajuste linear e estatistica -> gráfico de dispersão de dados em arquivos .txt fazendo ajuste um teste estatístico.
           1. dados: dados1.txt
       1. matriz de correlacao -> primeiro gráfico da correlação entre variáveis.
           1. dados: ind_sicio_econ.xlsx
    1. Com SPSS:
    
---
---

Casos:

Aqui são apresentados os casos que foram estudados, separados em pastas diferentes:

1. **Custos Médicos:** Calcula-se os custos médicos do plano de saúde para uma pessoa baseado em caraterísticas como Idade, Índice de masa corporal, Sexo, se é fumante ou não, etc. 
    1. Custos Médicos RL: Este é o primeiro e mais simple de todos, pois fue feito usando só técnicas **Regressão Linear** e considerando só duas das variáveis uma numérica (índice de massa corporal) e uma outra categórica (fumante). Posteriormente será feito com mais variáveis e com outras técnicas mais apropriadas para o estudo de variaveis categóricas como o **modelo-KNN**, etc.  
    2. Custos Médicos K-NN: Se estabelece uma comparação entre o cálculo anterior (**Regressão Linear**) e o **modelo-KNN** (usado como regressão e não como classificador)
    3. Custos Médicos 3: Melhora feita, usando mais variáveis independientes e diferentes modelos.
    4.
2. **Classificação de Flores (Iris):** Mostra-se a técnica classificação usando o **modelo de K-NN**
3. **?**

