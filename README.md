
# Análise Estatística com Python - Google Colab

Este repositório contém um notebook desenvolvido no Google Colab com foco em **análises estatísticas exploratórias**, ideal para estudantes ou profissionais que desejam aplicar estatística descritiva em conjuntos de dados reais usando Python.

## 🔍 Conteúdo do Notebook

O notebook aborda conceitos fundamentais e aplicações práticas de estatística, incluindo:

- 📊 **Tipos de amostragem**
- 📐 **Escalas de medição**
- 📈 **Medidas de tendência central** (média, mediana, moda)
- 📉 **Medidas de dispersão** (desvio padrão, variância, amplitude)
- 🧪 **Testes de normalidade** (Shapiro-Wilk, D’Agostino-Pearson)
- 🔗 **Correlação** (coeficiente de Pearson e Spearman)
- 📌 Análises com visualizações para facilitar a interpretação dos dados

## 📁 Acesso ao Notebook

Você pode acessar e executar o notebook diretamente no Google Colab por meio do link abaixo:

🔗 [Clique aqui para abrir o notebook no Colab](https://colab.research.google.com/drive/1CxTB0AITDrERKeyCHMWFOhPFtBvKpdTs#scrollTo=9Z0rRhfHANzZ)

## 📂 Utilização do Arquivo CSV

Para que o notebook funcione corretamente, é necessário **fazer o upload do arquivo `online_sales_data.csv` incluído neste repositório**.  

### ✅ Passos para utilizar:

1. Faça o download do arquivo [`online_sales_data.csv`](./online_sales_data.csv) presente neste repositório.
2. Acesse o notebook pelo Colab (link acima).
3. Na primeira célula de código, será solicitado o upload de um arquivo:
   ```python
   from google.colab import files
   uploaded = files.upload()
   ```
4. Clique no botão para selecionar e fazer o upload do arquivo `online_sales_data.csv`.
5. Após o upload, o notebook conseguirá carregar os dados corretamente e executar todas as análises estatísticas.
