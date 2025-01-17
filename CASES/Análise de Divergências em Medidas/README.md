# Resolução do Teste: Análise de Divergências em Medidas  

Este documento detalha o processo de investigação e solução do problema identificado no arquivo `DS_MEASURE.pbix`, onde a medida **REMAINING** apresenta valores incorretos ao ser convertida para USD.

Um analista identificou uma divergência em um dos gráficos, onde o valor exibido não corresponde ao esperado.
![image](https://github.com/user-attachments/assets/dae6ea96-cc5a-42c4-9c0d-9cfcef032666)

![image](https://github.com/user-attachments/assets/4e3bbca2-f75f-4bfb-a312-be25d3cc1975)

---

## 📝 Objetivo  

Investigar e diagnosticar a causa da divergência na medida **REMAINING** ao realizar a conversão para USD, garantindo que os cálculos estejam alinhados com os resultados esperados.  

---

## 🛠️ Processo de Investigação  

1. **Análise Inicial do Relatório:**  
   Revisão dos gráficos, tabelas e medidas diretamente ligadas à conversão para USD.  

2. **Exame das Dependências:**  
   - Identificação das medidas envolvidas no cálculo de **REMAINING**.  
   - Verificação de tabelas de conversão de moeda e possíveis problemas de relacionamento.  

4. **Correções Implementadas:**  
   - Ajustes nas expressões DAX relacionadas, se necessário.  
   - Verificação da integridade dos relacionamentos no modelo de dados.  
---

## 🖼️ Modelo de Dados  

O modelo de dados utilizado para a investigação está representado abaixo:  
![Modelo de Dados](https://github.com/user-attachments/assets/11a5e7c0-dca2-4772-b5fe-fedaa2f960df)  

---

## 🚀 Como Utilizar  

1. Abra o arquivo `DS_MEASURE.pbix` no **Power BI Desktop**.  
2. Revise as medidas ajustadas e os cálculos relacionados à conversão para USD. 