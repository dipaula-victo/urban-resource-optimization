# 🌐 Otimização da Distribuição de Produtos Essenciais em Cidades Inteligentes

Este projeto desenvolve e implementa um algoritmo de otimização para alocar dois tipos de produtos essenciais em grandes centros urbanos simulados (São Francisco, Nova Délhi e Pequim), com foco em **eficiência, cobertura, sustentabilidade e custo**.

---

## 🏙️ Contexto

Grandes cidades enfrentam desafios como:

- Transição para infraestrutura sustentável
- Logística eficiente em emergências sanitárias

O projeto busca modelar esses desafios como um problema de otimização combinatória, utilizando abordagens de algoritmos gulosos e programação dinâmica para encontrar soluções viáveis e eficientes.

---

## 🎯 Objetivo

Distribuir estrategicamente:

- **Produto A:** Estações sustentáveis (pontos de recarga, bicicletas compartilhadas)
- **Produto B:** Kits médicos de emergência

Maximizando cobertura e sustentabilidade, minimizando custos e respeitando restrições operacionais.

---

## 🧠 Metodologia

- Modelagem matemática do problema como uma **variante do problema de cobertura de conjunto**
- Implementação de um **algoritmo guloso com memoization**
- Avaliação de cenários em grafos urbanos simulados
- Comparação entre abordagens com e sem ponderação de custo

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- NumPy
- Plotly (visualizações interativas)
- NetworkX (modelagem de grafos)
- Google Colab
- Programação Dinâmica e Algoritmos Gulosos

---

## ⚙️ Compromissos Assumidos

Durante o desenvolvimento, foram considerados e equilibrados diversos compromissos críticos:

1. **Eficiência vs. Otimalidade**:  
   Algoritmo guloso é eficiente, mas não garante a solução ótima.

2. **Cobertura vs. Custo**:  
   A função de pontuação pondera cobertura (0.5), sustentabilidade (0.3) e custo (-0.2).

3. **Produto A vs. Produto B**:  
   Seleção conjunta pode causar desequilíbrio entre os produtos. Alternativas são discutidas.

4. **Simplicidade vs. Realismo**:  
   O modelo faz simplificações que o tornam viável, mas com limitações para aplicações diretas.

5. **Memoization vs. Memória**:  
   Acelera cálculos, mas aumenta o uso de memória.

---

## 📈 Resultados

As simulações mostraram que a abordagem gulosa baseada em benefício/custo:

- **Maximizou a cobertura dentro do orçamento**
- **Foi computacionalmente eficiente**
- **Permitiu comparações claras entre estratégias**

Cidades como **São Francisco, Nova Délhi e Pequim** responderam de maneira diferente às estratégias de distribuição, o que destaca a importância de modelos adaptáveis.

---

## 🧪 Contribuições Técnicas

- Formalização matemática do problema
- Algoritmo com complexidade O(l * z * (m + n log n))
- Uso de **programação dinâmica**, **memoization** e **estruturas de grafos**
- Visualizações interativas para análise urbana

---

## 🌍 Aplicações Práticas

- Planejamento urbano sustentável
- Logística de emergência
- Alocação de recursos públicos
- Otimização de redes urbanas inteligentes

---

## 📂 Organização do Projeto

```bash
📁 distribuicao-otima-cidades-inteligentes
│
├── distribuicao_otimizada.ipynb # Notebook principal
├── imagens/ # Visualizações dos resultados
└── README.md
