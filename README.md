# 📉 Análise de Evasão de Clientes - Telecom X

Este projeto tem como objetivo analisar dados de clientes da empresa **Telecom X**, que vem enfrentando uma alta taxa de evasão (churn). Através de técnicas de ETL (Extração, Transformação e Carga), análise exploratória (EDA) e modelagem preditiva, buscamos identificar os principais fatores que levam os clientes a cancelar seus serviços.

---

## 🧪 Tecnologias Utilizadas

- Python 3.10+
- Pandas
- `Seaborn`
- Matplotlib
  
---

## 🔍 Objetivos da Análise

- Identificar perfis de clientes com maior propensão ao cancelamento.
- Explorar padrões relacionados a tipo de contrato, tempo de permanência e gastos.
- Gerar insights para auxiliar a empresa em estratégias de retenção.

---

## 🛠️ Processo ETL

1. **Extração**: Dados carregados diretamente de um arquivo `.json` disponível no GitHub.
2. **Transformação**:
   - Conversão de tipos de dados.
   - Tratamento de nulos e duplicados.
   - Codificação de variáveis categóricas.
3. **Carga e Análise**:
   - Geração de visualizações com `seaborn` e `matplotlib`.
---

## 📊 Principais Insights

- Clientes com **contratos mensais** são os que mais cancelam.
- **Baixo tempo de relacionamento** e **menor gasto total** estão associados a maior evasão.
- Estratégias de retenção devem focar nos **primeiros meses de contrato**.
- Modelos preditivos podem auxiliar no monitoramento de **clientes em risco**.

---

## 📁 Execução

1. Repositório:
   ```bash

