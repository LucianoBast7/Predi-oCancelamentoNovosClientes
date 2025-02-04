# 📊 Predição de Cancelamento de Clientes - Orange Data Mining

Este projeto utiliza **Orange Data Mining** para prever quais clientes de um serviço de streaming têm maior probabilidade de cancelar a assinatura. Utilizando aprendizado de máquina, analisamos padrões de comportamento e fatores que influenciam a retenção de clientes.

## 📌 Objetivo
Criar um modelo preditivo que identifique **clientes propensos ao churn**, ajudando a empresa a desenvolver estratégias para reduzir cancelamentos.

## 🚀 Tecnologias Utilizadas
- [Orange Data Mining](https://orangedatamining.com/) - Plataforma visual de aprendizado de máquina.
- Algoritmos: **Regressão Logística** para previsão.
- Pré-processamento de dados: Normalização e remoção de valores nulos.

## 📂 Estrutura do Workflow no Orange
O fluxo de trabalho no Orange foi construído com os seguintes componentes:

1️⃣ **File** → Carregamento do conjunto de dados `churn_data.csv`.  
2️⃣ **Data Table** → Visualização dos dados.  
3️⃣ **Preprocess** → Normalização e tratamento de valores ausentes.  
4️⃣ **Select Columns** → Escolha das variáveis mais relevantes:  
   - **Idade**  
   - **Tempo de Assinatura**  
   - **Frequência de Uso Semanal**  
   - **Quantidade de Filmes/Séries Mensal**  
   - **Valor da Mensalidade**  
   - **Variável alvo: Cancelou (0 = não cancelou, 1 = cancelou)**  
5️⃣ **Logistic Regression** → Modelo de aprendizado de máquina.  
6️⃣ **Test & Score** → Avaliação da precisão do modelo.  
7️⃣ **Confusion Matrix** → Validação dos resultados.  
8️⃣ **Predictions** → Aplicação do modelo para prever churn em novos clientes.  

## 🔧 Como Executar o Projeto
1. **Baixe e instale o Orange Data Mining**  
   🔗 [Download Orange Data Mining](https://orangedatamining.com/download)  
2. **Baixe os arquivos do projeto**:
   - 📄 `churn_data.csv` (conjunto de dados de clientes)
   - 📄 `new_clients_data.csv` (novos clientes para predição)
   - 📂 `churn_prediction.ows` (workflow no Orange)
3. **Abra o arquivo `.ows` no Orange**:
   - Execute o Orange Data Mining.
   - Vá em **"File" > "Open"** e selecione `churn_prediction.ows`.
4. **Execute o workflow** clicando no botão de **Play**.
5. **Analise os resultados**:
   - Verifique as métricas do modelo na aba **Test & Score**.
   - Consulte a **Confusion Matrix** para avaliar a precisão da predição.
   - Use o widget **Predictions** para prever o churn de novos clientes.

## 📊 Insights Obtidos
- **Clientes com menor tempo de assinatura têm maior propensão ao cancelamento.**
- **Baixa frequência de uso e poucos filmes assistidos indicam maior risco de churn.**
- **Planos mais caros não garantem retenção, especialmente quando o engajamento é baixo.**
- **O método de pagamento influencia: clientes que pagam via Pix/Boleto tendem a cancelar mais do que os que usam cartão de crédito.**

## 📌 Conclusão
Este modelo ajuda a empresa a **prever o churn e criar estratégias personalizadas** para retenção, como:
✅ Oferecer **descontos para clientes novos**.  
✅ Criar campanhas para **aumentar o engajamento**.  
✅ Melhorar a **personalização de recomendações** para usuários de risco.  

---

📬 **Contato**: Caso tenha dúvidas ou queira colaborar, entre em contato! 🚀  
