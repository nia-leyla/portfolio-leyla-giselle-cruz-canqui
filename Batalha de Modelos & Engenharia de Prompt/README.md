# 📑 Relatório Técnico: Engenharia de Prompt & Aplicações em IA

Este projeto apresenta uma análise comparativa detalhada sobre a eficácia de diferentes modelos de linguagem (LLMs) ao processarem instruções estruturadas em XML para o desenvolvimento de interfaces Web. 

---

## 👥 Integrantes do Grupo
* **Pedro Martins Rodrigues Alves** 
* **Leyla Giselle Cruz Canqui** 
* **Aleksandro Soares Oliveira** 

---

## 🎯 Objetivo do Experimento
Construir um **Prompt Estruturado em XML** para a geração de uma *Single Page Application* (SPA) focada no setor financeiro. 

### 🎨 Especificações de Design (XML Input)
* **Tema:** Finanças e Investimentos. 
* **Paleta:** 🌑 Preto, 🟣 Roxo e 🔵 Azul. 
* **Layout:** Minimalista e Responsivo. 
* **Tipografia:** Títulos em Sans-serif e corpo em Serif. 
* **Funcionalidades:** Menu com âncoras, galeria/portfólio e conversão de moedas (Dólar, Real, Euro). 

---

## 📊 Quadro Comparativo de Performance
Abaixo, a análise técnica de como cada IA se comportou durante a tarefa: 

| Critério | GPT | Gemini | DeepSeek | Qwen | Grok | Maritaca | Claude |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Precisão Geral** | Alta | Baixa | Alta | Média | Alta | Baixa | **Máxima** |
| **Interface/HTML** | Baixa | Baixa | Alta | Média | Instável | Ruim | **Fluida** |
| **Bugs Encontrados** | Nenhum | Gráficos | Nenhum | Imagens | Botões | Vários | **Nenhum** |
| **Gasto de Tokens** | 1150 | 1300 | 2100 | 1250 | 2850 | 1200 | 6200 |

---

## 💡 Reflexão Crítica & Conclusões

### 1. Compreensão de Estrutura
O modelo **Claude** foi o que demonstrou maior capacidade de interpretar e seguir rigorosamente a hierarquia das tags XML fornecidas. 

### 2. Eficiência vs. Verbosidade
Notou-se uma variação extrema no consumo de tokens: enquanto o **ChatGPT** entregou um código funcional com apenas **1150 tokens**, o **Claude** utilizou **6200 tokens** para garantir maior refinamento e interatividade. 

### 3. Recomendação de Uso
* **Prototipagem Rápida:** O **ChatGPT** é ideal pela velocidade e baixo custo de processamento. 
* **Sistemas Complexos:** O **Claude** é a ferramenta recomendada para códigos que exigem maior precisão lógica e interfaces robustas. 
### 4. link para baixar o pdf [Trabalho_pagina.pdf_20260328_212234_0000.pdf](https://github.com/user-attachments/files/27552481/Trabalho_pagina.pdf_20260328_212234_0000.pdf)

---
> **Nota:** Este experimento foi testado em diversas ferramentas incluindo ChatGPT, Gemini, Claude, Qwen, DeepSeek, Grok e Maritaca.
