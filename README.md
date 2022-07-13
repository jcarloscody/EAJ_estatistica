# **PESQUISA DE ESTATÍSTICA**


## **DESCRIPTIVE STATISTICS | Kaggle**
Segundo o Google, a Estatística é o “ramo da matemática que trata da coleta, da análise, da interpretação e da apresentação de massas de dados numéricos”. Então, podemos concluir que a estatística é capaz de analisar um levante de circunstância e problemas através de seus variados conceitos.

**`Média:`**
- É de tendência **central**;
- Indica o valor onde estão concentrados os dados de um conjunto de valores.
```sh
import pandas as pd
import numpy as np

series =  pd.Series([1,5,10,30,50,30,15,40,45])

print(series.mean())
25.11111111111111
```

**`Mediana:`**
- Separa a **metade superior** da **metade inferior** de uma distribuição de dados;
- A mediana é um conceito menos suscetível a grandes valores discrepantes do que a média. 
```sh
print(series.median())
30.0
```

**`Moda`**
- É o valor que mais se repete;
```sh
print(example_series.mode())
0    30
```

**`Amplitude`**
- A amplitude nada mais é do que a diferença entre o **maior e o menor valor** de um conjunto de dados.
  
```sh
print(series.max() - series.min())
49
```

**`Variância`**
- Expressa quanto os dados de um conjunto estão **afastados de seu valor esperado.**

```sh
print(series.var())
325.1111111111111
```

**`Desvio Padrão`**
-  Indica quanto os dados estão **afastados da média.**

```sh
print(series.mad())
15.432098765432098
```

## **DESCRIPTIVE ANALYSIS | Kaggle**
O objetivo da análise descritiva é procurar a `existência de padrões` que podem ser mapeados.
Ela é muito usada no meio acadêmico porque este tipo de análise **serve de suporte para explicar** um determinado fim.

Apesar de apresentar como **`vantagem`** o suporte **imparcial** como fonte para as pesquisas, pode em algum momento ser **`desvantajosos`** causar prejuízo, pois a amostra pode ser mal escolhida.


#### **OS 5 NÍVEIS** 
- Identificação do Problema;
- Recolhimento dos Dados;
- Crítica dos Dados;
- Apresentação dos Dados;
- Análise e Interpretação.


### **FONTES**

https://www.fiveacts.com.br/analise-descritiva/

https://www.youtube.com/watch?v=yS4ygMSvy3w

https://www.infoescola.com/estatistica/medidas-de-dispersao/
