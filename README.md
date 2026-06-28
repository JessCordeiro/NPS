# NPS

Esse projeto visa entender como variáveis operacionais afetam o NPS, de modo a ajudar a melhorar seus processos e experiência dos clientes

## 📊 Visão Geral
Dados foram analisados através da base contida em arquivo csv e analisados com auxílio de bibliotecas de manipulação de dados.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python 3.x
* **Ambiente:** Google Colab
* **Principais Bibliotecas:**
  * `Pandas` (Manipulação de dados)
  * `Matplotlib` / `Seaborn` (Visualização)
  * `plotly.express` (Visualização)
  * `pearsonr` (Correlação de Pearson)

## 📁 Estrutura do Repositório
* `dados/`: Contém os arquivos `.csv`.
* `notebooks/`: Onde está o arquivo `.ipynb` com a análise passo a passo.
* `README.md`: Este arquivo de documentação.

## 🚀 Como Executar o Projeto

Como este projeto foi desenvolvido no **Google Colab**, você não precisa instalar nada na sua máquina local. Existem duas formas de visualizar e executar a análise:

### Opção 1: Abrir Diretamente no Google Colab (Recomendado)
1. Certifique-se de estar logado em uma conta Google.
2. Acesse o notebook clicando no link abaixo:
   > 🔗 [**Clique aqui para abrir o projeto no Google Colab**](https://colab.research.google.com/drive/1iXel27_6IMayiiRzPJSNZpSVP1wLhjxC?usp=sharing)
3. Para executar o código e fazer alterações, vá em **Arquivo > Salvar uma cópia no Drive**.
4. Certifique-se de fazer o upload dos arquivos da pasta `dados/` para o ambiente do Colab antes de rodar as células (caso os dados não estejam sendo puxados diretamente por uma URL pública).

### Opção 2: Baixar e Executar Localmente
Caso prefira rodar no seu próprio ambiente local (Jupyter Notebook):
1. Clone este repositório:
   ```bash
   git clone https://github.com/JessCordeiro/NPS.git

## 💡 Principais Insights e Conclusões
Como resultado pode-se perceber que fatores como dias de atraso na entrega, número de reclamações e contatos do cliente estão fortemente correlacionados.

