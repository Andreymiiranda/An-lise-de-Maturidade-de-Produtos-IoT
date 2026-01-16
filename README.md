# 📊 Desafio de Data Analytics: Análise de Maturidade de Produtos IoT

---

## 1. Contexto do Cenário

Você acaba de integrar o time de **Inteligência de Dados** da **TechNova Incubator**, uma aceleradora focada em investir em startups de **hardware** e **Internet das Coisas (IoT)**.

Atualmente, o time de engenharia técnica realiza uma bateria de testes rigorosos nos protótipos das startups, gerando uma pontuação chamada **Tech Score**.

Essas avaliações são fundamentais para apoiar decisões estratégicas de investimento.

---

## 2. O Problema

O processo atual de avaliação é **manual**.

Os engenheiros preenchem planilhas individuais para cada startup, o que gera:

- Falta de padronização  
- Dificuldade de consolidação das informações  
- Pouca visibilidade para a diretoria  

Como consequência, a liderança não possui uma visão clara sobre **quais startups apresentam maior maturidade técnica** para receber investimentos.

A organização precisa evoluir de *“planilhas soltas”* para uma **cultura orientada a dados**, permitindo decisões mais rápidas, seguras e estratégicas.

---

## 3. Sua Missão

Como **Analista de Dados**, sua missão é estruturar a **fundação analítica** desse processo.

Você recebeu um dump de dados brutos (`tech_score_data.csv`) contendo avaliações recentes de **45 startups**, com os seguintes objetivos:

- Organizar os dados de forma estruturada  
- Tratar inconsistências e valores ausentes  
- Criar métricas consolidadas por critério técnico  
- Gerar análises que apoiem a tomada de decisão  
- Construir visualizações claras e acionáveis  

---

## 4. Descrição dos Dados

O dataset contém avaliações técnicas distribuídas em **8 grandes critérios**, cada um composto por múltiplos indicadores:

1. Performance  
2. Viabilidade  
3. Confiabilidade  
4. Usabilidade  
5. Energia  
6. Físico  
7. Conectividade  
8. Ciclo de Vida  

Cada critério foi consolidado a partir da **média dos seus respectivos indicadores**.

---

## 5. Análises Realizadas

- Limpeza e preparação dos dados  
- Agrupamento de indicadores por critério  
- Cálculo de score médio por startup  
- Análise comparativa de maturidade técnica  
- Visualização dos critérios utilizando **gráfico de radar**  

---

## 6. Visualizações

As principais visualizações incluem:

- Gráfico de radar para avaliação multidimensional  
- Comparação entre startups  
- Identificação de pontos fortes e fracos por critério  

> 📌 As imagens estão disponíveis na pasta `/images`.

---

## 7. Tecnologias Utilizadas

- **Python**  
- **Pandas** (manipulação e análise de dados)  
- **Matplotlib** (visualização de dados)  
- **Jupyter Notebook**  

