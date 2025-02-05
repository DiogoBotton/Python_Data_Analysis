# Python_Data_Analysis
Repositório com a finalidade de estudar as bibliotecas de análise de dados Pandas, NumPy e outros.

### **Explicação sobre o que representam os Quartis**

1° Quartil (25%):
- Representa o **valor abaixo do qual 25%** dos dados estão abaixo, por exemplo, a coluna **Age (idade)** é 20 (arredondado), ou seja, **25% dos passageiros tem menos de 20 anos**.

2° Quartil (50%):
- Representa o **valor abaixo do qual 50%** dos dados estão abaixo. A coluna *Age* é 28, ou seja, **50% dos passageiros tem idade inferior a 28 anos**, assim como, **50% dos passageiros tem idade superior a 28 anos**.

3° Quartil (75%):
- Representa o **valor abaixo do qual 75%** dos dados estão abaixo. A coluna *Age* é 38, ou seja, **75% dos passageiros tem idade inferior a 38 anos**, assim como, **25% dos passageiros tem idade superior a 38 anos**.

**Para que servem?**

Os quartis ajudam a resumir e entender a distribuição dos dados sem precisar olhar todos os valores, identificando valores baixos, médios e altos. Na estátistica e análise de dados, são usados também para **detectar outliers** (valores extremos).

**Como são detectados os outliers?**

Se um dado está **muito abaixo** do 1° Quartil (Q1 - 25%) ou **muito acima** do 3° Quartil (Q3 - 75%), pode ser um valor atípico.

**Mediana**

O 2° Quartil (Q2) também pode ser considerada como a **mediana**, pois é o valor central de um array ordenado.

- Caso o número de elementos for **ímpar**, a **mediana é o valor central**.
- Caso o número de elementor for **par**, a **mediana é a média dos dois valores centrais**.

### **Explicação sobre desvio padrão**

O **desvio padrão** é uma medida da **dispersão** dos dados **em torno da média**. Ele indica o quão espalhados os valores estão em relação à média. Um desvio padrão alto significa que os dados estão mais dispersos (os valores estão distantes da média), enquanto um desvio padrão baixo significa que estão mais próximos da média.