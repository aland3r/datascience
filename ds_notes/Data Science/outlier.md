---
aliases:
definição: um ponto frequentemente muito distante dos outros.
---
primeiro passo para detectar o outlier, ordenar valores ( 156, 159, 162, 173, ... 280) e dertrminar Q1(25%) e Q2(75%). 
Q1 = 160
Q2 = 190
proximo passo, calcula o [[IQR]]
x < 1600 - 45
ou
x > 190 + 45 = 235

prova não pode calculadora

a fórmula acima funciona apenas com dados estatisticos
df.select_dtypes(include='number')




Outliers são dependentes de contexto, não são universais. Para quem trablhaa em múltiplas bases de dados, o outliers precisam ser tratados por cada dataset. 

por que eles aparecem?
- erro de aquisição (problema em sensor, por exemplo) ou inserção errada)
- pode ser legítimo

quando se pode considerar o outlier um errro de registro, então pode-se eliminar


out, liar!!

poucos dados acabam sendo eliminado.


para o nosso dataframe (asteroides) é mais difícil determinar o que se mantém ou elimina

qdo o dado vem de multiplas fontes, é comum ver diferenças como milhas e quilômetros, por exemplo.

outlier detection with box plots
outlier detection with Tukey's method


Tukey's method é usado para fazer o box plot

!!!!!!!!!!!!! TERÁ UM BOXPLOT PARA INTERPRETAR NA PROVA


metodo supervisionado vs não supervisionado pra detecção do outlier