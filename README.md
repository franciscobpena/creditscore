# Score de Crédito para Empréstimos Pessoais

## Contexto

Este projeto desenvolve um modelo de credit scoring para avaliar novos solicitantes de empréstimos pessoais. 
O modelo utiliza dados históricos de clientes que tiveram empréstimos aprovados anteriormente, com o objetivo de prever o risco de crédito de futuros solicitantes.

## Conclusões

O modelo de credit scoring desenvolvido apresenta as seguintes características e resultados:

* **Variáveis do modelo final:**
  * QTDE_EMPRESTIMOS_12M
  * QTDE_CHEQUE_ESPECIAL_12M
  * QTDE_PGTOS_EM_ATRASO_12M
  * VALOR_PGTOS_12M
  * FLAG_PGTO_PARCIAL_12M

* **Ponto de corte ótimo:** 0.84

* **Desempenho do modelo:**
  * Acurácia: ~60%
  * Especificidade: ~64%
  * Sensibilidade: ~59%
  * AUC: ~0.66
  * KS: ~0.26

O modelo demonstra um desempenho aceitável, sem evidências de overfitting. No entanto, há margem para melhorias em seu poder preditivo.

## Metodologia utilizada

- Análise Exploratória de Dados (EDA);
- Análise do Poder Preditivo das Variáveis;
- Modelagem com Regressão Logística;
- Avaliação de Desempenho do Model.

## Próximos Passos

1. Calcular e interpretar scores para clientes específicos.
2. Explorar a inclusão de novas variáveis preditivas ou criação de features derivadas.
3. Investigar técnicas de balanceamento de classes.
4. Testar algoritmos alternativos de machine learning (ex: Random Forest, Gradient Boosting).
5. Refinar o modelo com base em feedback de implementação prática.




