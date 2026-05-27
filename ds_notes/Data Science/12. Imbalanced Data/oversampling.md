
estratégia para equilibrar os dados
vamos aumentar o número de instâncias de asteroides não perigosos.

risco: criar um overfitting nas poucas amostras, ou mesmo amostras q não podiam existir no mundo real

# random oversampling
duplica aleatoriamente amostras da classe minoritária

ponto fraco: não cria novas informações, o modelo vai memorizar dados duplicados.
na pratica acaba funcionando, é simples

dependendo do classificador e modelo, ajuda, mas o caso dos asteroide é mais desafiador

no exemplo do slides:
se for acuracia global, grafico da esquerda melhor


# smoothed random oversampling
- ao invés de duplicar exatamente, basicamente adicionamos um pequeno ruído.

será q esse funciona melhor: (smootherd bootstrap do slide funciona melhor), normal atrapalha em algunas situações mas nao entendi se com mais ou menos

faz sentido qdo os novos dados fazem sentido para o problema, mas vom vairaveis ineiras fica mais complexo

# SMOTE

geralmente funciona bem

gera novas amostras pra classe minoritaria com interpolação
- synthetic minority oversampling technique

limitação, ele vai amplificar o outlier, gerando mais ruído
