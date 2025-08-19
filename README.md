# Projeto de Análise de Evasão de Clientes (Churn) na Telecom X

## 📄 Descrição do Projeto

Este projeto tem como objetivo principal realizar uma análise de dados sobre a evasão de clientes (conhecida como "Churn") da empresa de telecomunicações **Telecom X**. O desafio foi abordar o problema desde a coleta e o tratamento dos dados até a geração de insights e recomendações estratégicas para a gestão da empresa.

## 🚀 Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Pandas:** Para manipulação e tratamento de dados (ETL).
* **NumPy:** Para operações numéricas.
* **Matplotlib & Seaborn:** Para a criação de visualizações de dados (EDA).
* **Google Colab:** Ambiente de desenvolvimento para o notebook.
* **GitHub:** Para versionamento e hospedagem do projeto.

## 📂 Estrutura do Projeto

O projeto é apresentado em um único notebook, dividido nas seguintes seções:

* **Extração de Dados:** Coleta dos dados de uma API no formato JSON.
* **Transformação de Dados:** Processo de limpeza, tratamento, criação de novas variáveis e tradução de colunas e valores.
* **Análise Exploratória de Dados (EDA):** Análise estatística e visual dos dados para identificar padrões e tendências.
* **Relatório Final:** Apresentação de um relatório conciso com as conclusões e recomendações.

## 📈 Análises e Resultados

### Taxa de Evasão Geral

A análise inicial revelou uma taxa de evasão de **26.6%** dos clientes, um valor que indica a necessidade de ações imediatas de retenção.

### Fatores-Chave de Evasão

As análises exploratórias identificaram os seguintes fatores como os mais influentes na decisão de cancelamento dos clientes:

* **Tipo de Contrato:** Clientes com contratos **Mensais** têm a maior taxa de evasão, o que sugere uma baixa fidelização e facilidade de cancelamento.
* **Método de Pagamento:** O método de pagamento por **Cheque Eletrônico** está fortemente correlacionado com uma alta taxa de evasão, enquanto métodos automáticos apresentam taxas significativamente menores.


## 🎯 Conclusões e Recomendações

Com base nos insights obtidos, as seguintes recomendações estratégicas são propostas para a Telecom X:

1.  **Programas de Fidelização:** Criar incentivos para que clientes com contratos mensais migrem para planos anuais ou de dois anos.
2.  **Promoção de Métodos de Pagamento Automáticos:** Oferecer bônus ou descontos para clientes que optarem por métodos de pagamento como cartão de crédito ou transferência bancária automática.
3.  **Melhoria da Experiência Digital:** (Adicione aqui recomendações específicas com base nos seus achados, como "Melhorar a plataforma de pagamento por cheque eletrônico").
