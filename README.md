# Análise-tendencias-mercado
Projeto de análise exploratória de dados públicos para identificar padrões de consumo e tendências, utilizando bibliotecas de visualização.

🛠 Tecnologias

Python
Pandas
Matplotlib

ESTRUTURA
 ├── data/
 │   └── vendas.csv
 ├── images/
 │   └── grafico.png
 ├── analise_tendencias.py
 └── README.md

🖥️ Como Executar

    pip install pandas matplotlib
    Executar analise_tendencias.py

CÓDIGO BASE

import pandas as pd  
import matplotlib.pyplot as plt  

data = pd.read_csv('data/vendas.csv')  
data['vendas'].plot()  
plt.title('Tendência de Vendas')  
plt.savefig('images/grafico.png')  
plt.show()  

✅ Resultado

Visualização gráfica clara das tendências de consumo.
