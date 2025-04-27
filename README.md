# 📊 Análise de Comportamento de Clientes

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-green)

Projeto final do **CURSO FIC - Introdução ao Python e Visualização de Dados**, desenvolvido para aplicar conceitos de análise exploratória (EDA), estatística descritiva e visualização de dados.  

---

## 🔍 Objetivos Cumpridos
1. **Cálculo de métricas**:  
   - Média de idade, renda, compras online e satisfação  
2. **Análise de correlação**:  
   - Renda mensal vs. número de compras online  
3. **Segmentação por gênero**:  
   - Médias de satisfação e compras por grupo  
4. **Visualizações**:  
   - Gráfico de dispersão e barras  
5. **Filtragem estratégica**:  
   - Clientes com >30 anos e <5 compras online  
6. **Identificação de outliers**:  
   - Na variável "Renda Mensal"  

---

## 📋 Resultados Principais
### Estatísticas Descritivas
| Métrica               | Valor               |
|-----------------------|---------------------|
| Média de Idade        | 41 anos             |
| Média de Renda Mensal | R$ 5.712,33         |
| Média de Compras      | 14.8 compras/mês    |
| Média de Satisfação   | 4.7/10              |

### Correlação Renda x Compras
- **Coeficiente**: `-0.08` (fraca correlação negativa)  
- **Interpretação**: Não há relação significativa entre as variáveis.

### Análise por Gênero
| Gênero       | Renda Média     | Compras Médias | Satisfação |
|--------------|-----------------|----------------|------------|
| Não-Binário  | R$ 5.816,67     | 12.9           | 5.2/10     |
| Feminino     | R$ 5.598,71     | 16.9           | 4.7/10     |
| Masculino    | R$ 5.736,52     | 14.5           | 4.3/10     |

### Clientes Prioritários
- **11 clientes identificados** (>30 anos e <5 compras online).  
- **Ação sugerida**: Campanhas de engajamento personalizadas.

### Outliers
- **Limite superior (IQR)**: R$ 14.903,62  
- **Outliers detectados**: 0  

---
