---
aliases:
  - dados desbalanciados
---
# class imbalance

foco em classificação, mas serve para regressão
teremos valores muito concentrados e oss outros nao serao mostrados no dataset. como lidar com isso?

muito comum em [[Machine Learning]]
quando a distribuição de classes está extremamente enviesado (skewed)

duas estratégia pra mitigar desequilibrio de dados
- outras:
	- class weighting
	- threshold tuning
	- cost-sensitive learning
	- ensemble-based methods

melhor resultadoé misturar os métodos acima com oversampling/undersampling (???)

biblioteca imblearn
