# 🐍 Analytics com Python - Dashboard de Análise de Salários na Área de Dados  

## ☝️ Sobre o projeto...  
Projeto de análise de dados de salários na área de Dados utilizando Python.
  
## 🛠️Stack Tecnológica  
* **Linguagem:** Python 3  
* **Bibliotecas:** Pandas (carregamento e tratamento dos dados), Plotly (plotagem dos gráficos) e Streamlit (interface/dashboard).
  
## 🎲 Estrutura dos Dados  
O raw do dataset utilizado pode ser encontrado no [link](https://raw.githubusercontent.com/danilo-s-reis/datasets/refs/heads/main/salarios_dados.csv) anexado.
* **Origem:** Dataset do Kaggle tratado no Colab.
* **Dicionário de Dados:** `salarios_dados.csv`  

| Nome do Campo | Descrição | Tipo de Dado | Exemplo | Observações |
| :--- | :--- | :--- | :--- | :--- |
| `ano` | Ano em que foi feito o registro. | `int64` | `2023` | Dados de 2020 até 2025 |
| `senioridade` | Nível de experiência no cargo. | `Object` | `Senior` | Junior<br>Pleno<br>Senior<br>Executivo |
| `contrato` | Tipo de contrato para a função. | `Object` | `Tempo Integral` | Tempo Integral<br>Tempo Parcial<br>Contrato<br>Freelance |
| `cargo` | Nome do cargo. | `Object` | `Data Scientist` | |
| `salario` | Valor do salário anual na moeda local | `int64` | `80000` | |
| `moeda` | Moeda do salário pago. | `Object` | `EUR` | Moeda representada pelo código ISO 4217. |
| `usd` | Salário convertido para dólares americanos (USD). | `int64` | `85847` | |
| `residencia` | País de residência do funcionário. | `Object` | `ES` | País representado pelo código ISO 3166-2. |
| `remoto` | Tipo de trabalho. | `Object` | `Presencial` | Presencial<br>Remoto<br>Híbrido |
| `empresa` | País do local da empresa. | `Object` | `US` | País representado pelo código ISO 3166-2. |
| `tamanho_empresa` | Tamanho da empresa. | `Object` | `Grande` | Pequena<br>Média<br>Grande |
| `residencia_iso3` | Coluna de conversão do código ISO 3166-2 de `residencia` em código ISO 3166-3 | `Object` | `USA` | Coluna usada exclusivamente para o gráfico coroplético |

## 🚀 Como rodar o projeto localmente  
### Pré-requisitos
- Python 3  
### Passos  
1. **Clone o repositório:**
```bash
git clone https://github.com/danilo-s-reis/analytics-python-salarios.git  
```  
2. **Instale as dependências:**  
```bash
pip install -r requirements.txt
```  
3. **Execute o app Streamlit:**  
```bash
streamlit run app.py
```  
## 📫 Contato

Vamos nos conectar!

-   **LinkedIn:** [danilo-souza-reis](https://www.linkedin.com/in/danilo-souza-reis-ab61761b6/)
-   **GitHub:** [@danilo-s-reis](https://github.com/danilo-s-reis)
-   **Email:** [reis.souza.danilo@hotmail.com](mailto:reis.souza.danilo@hotmail.com)  
  
## 🌐 Link deploy  
Você pode ver o dashboard gerado clicando [aqui](https://github.com/danilo-s-reis/analytics-python-salarios).