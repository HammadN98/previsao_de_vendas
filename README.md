# Previsão de Vendas - Rossmann

---
Como prever as vendas diárias das lojas Rossmann para otimizar o planejamento de estoques e alocação de recursos?
---
Destaque do Projeto
Este projeto aborda a previsão de vendas em uma das maiores redes de varejo da Europa.
Usando aprendizado de máquina, o modelo escolhido (XGBoost) atingiu uma explicação de 95% da variabilidade das vendas e um erro médio de apenas 926 unidades.
A previsão pode ser usada por gerentes para otimizar estoques e escalas de funcionários, garantindo eficiência operacional.
Dados como feriados, promoções e concorrência foram cuidadosamente analisados e tratados para maior precisão nas previsões.

| Modelo             | Melhor RMSE | RMSE Médio | Desvio Padrão (RMSE) | Tempo de Execução (s) |
|--------------------|-------------|------------|-----------------------|------------------------|
| XGBoost           | **959.11**  | **926.20** | **6.32**             | **30.83**             |
| Random Forest      | 1286.79     | 1254.14    | 21.29                | 3337.05               |


