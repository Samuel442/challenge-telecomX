# 📊 Análise de Evasão de Clientes (Churn Analysis)

## 📌 Descrição do Projeto
Este projeto analisa o comportamento de evasão de clientes (**Churn**) em uma empresa de telecomunicações. O foco é identificar padrões e fatores que influenciam o cancelamento de serviços para gerar **insights estratégicos** que auxiliem na retenção de clientes.

## 🎯 Objetivos
* Entender o perfil demográfico e comportamental dos clientes que evadem.
* Identificar variáveis críticas associadas ao cancelamento.
* Analisar o impacto do tempo de contrato e das cobranças financeiras.
* Propor recomendações acionáveis para redução do churn.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib, Seaborn
* **Ambiente:** Google Colab / Jupyter Notebook

---

## 🧹 Limpeza e Tratamento de Dados
Para garantir a qualidade da análise, foram realizadas as seguintes etapas:
* Tratamento de valores ausentes e conversão de tipos numéricos.
* Padronização de categorias e renomeação de colunas.
* **Feature Engineering:** Criação da variável *Cobrança Diária*.
* **Preprocessing:** Codificação de variáveis categóricas (**One-Hot Encoding**).

## 🔎 Análise Exploratória de Dados (EDA)
As principais frentes de investigação foram:
1. Distribuição Geral da Evasão.
2. Relação entre **Tempo de Contrato** e Churn.
3. Impacto do **Tipo de Contrato** (Mensal vs. Anual).
4. Análise de métricas financeiras (Cobranças Mensal/Diária/Total).
5. Evasão por variáveis categóricas (Internet, Pagamento e Gênero).
6. Matriz de Correlação entre variáveis numéricas.

---

## 📈 Principais Insights
* **Janela de Risco:** A evasão ocorre majoritariamente nos primeiros meses de contrato.
* **Modelo Contratual:** Contratos mensais apresentam churn significativamente maior que os anuais.
* **Tecnologia e Pagamento:** Clientes com *Fiber optic* e pagamento via *Electronic check* têm maior risco de evasão.
* **Fator Custo:** Valores elevados de cobrança diária e mensal estão correlacionados ao churn.
* **Fator Neutro:** O gênero não apresenta influência relevante na decisão de cancelamento.

## 💡 Recomendações
* Incentivar a migração de contratos mensais para planos de longa duração.
* Implementar ações de **onboarding** e retenção nos primeiros 90 dias do cliente.
* Oferecer benefícios para adesão a métodos de pagamento automáticos.
* Revisar a política de preços e qualidade do serviço de Fibra Óptica.
