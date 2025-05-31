# 📊 Telecom X – Análise de Evasão de Clientes (Churn)

Este projeto foi desenvolvido como parte do desafio de Data Science do Programa ONE (Oracle Next Education), com foco no processo de ETL e análise exploratória de dados para entender os fatores que influenciam a evasão de clientes em uma empresa de telecomunicações fictícia, a Telecom X.

---

## 📌 Objetivo

O principal objetivo é identificar padrões de comportamento entre clientes que cancelaram o serviço (`Churn = 1`) e aqueles que permaneceram, utilizando técnicas de ETL, limpeza de dados, visualizações e análise descritiva.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Estrutura do Projeto

- `TelecomX_BR.ipynb`: notebook principal contendo todas as etapas do projeto.
- `README.md`: este arquivo de apresentação do projeto.
- Dados extraídos diretamente da [API JSON do GitHub](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/main/TelecomX_Data.json)

---

## 🧪 Etapas Realizadas

1. **Extração dos Dados**: Dados obtidos via API em formato JSON e carregados com `pandas.read_json()`.
2. **Transformação**:
   - Normalização de colunas aninhadas
   - Limpeza e tratamento de inconsistências
   - Criação de novas variáveis (`Contas_Diarias`, `Qtd_Servicos`)
   - Conversão de categorias binárias para 0/1
   - Renomeação de colunas para melhor leitura
3. **Análise Exploratória (EDA)**:
   - Análise descritiva das variáveis
   - Visualização da distribuição de `Churn`
   - Análises por variáveis categóricas e numéricas
   - Correlação entre variáveis (extra)

---

## 📈 Resultados e Insights

- Clientes com menor tempo de contrato e faturas mais altas evadem mais.
- Contratos mensais e pagamento por `Electronic Check` têm maior associação com churn.
- A maioria dos clientes permanece com a empresa, mas há um padrão claro de risco entre perfis específicos.

---

## 👨‍💻 Autor
Este projeto foi desenvolvido por Jorge Fernandes, participante do Programa ONE | Alura + Oracle.
