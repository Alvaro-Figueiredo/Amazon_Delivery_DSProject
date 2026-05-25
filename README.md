Seguirei o método STAR para documentar esse projeto.

No ecossistema de e-commerce A dificuldade em estimar com precisão o Tempo Estimado de Chegada (ETA) gera um dilema de negócios direto: prometer um prazo excessivamente longo reduz a conversão de vendas na tela de checkout, enquanto prometer um prazo muito curto e falhar resulta em insatisfação do cliente, aumento nos custos de suporte (SAC) e devoluções.

---

O presente projeto de Ciência de Dados utiliza um conjunto de informações públicas de operações logísticas extraído do Kaggle (Amazon Delivery Dataset) para enfrentar esse gargalo analítico.

---

O objetivo primário deste projeto é desenvolver um modelo preditivo de Regressão capaz de estimar o tempo real de entrega (Delivery_Time) com alta precisão matemática, antecipando as condições operacionais antes mesmo que a entrega inicie.

Para guiar o desenvolvimento do modelo e a etapa de Análise Exploratória (EDA), estabelecemos as seguintes hipóteses analíticas a serem validadas:

H1 (Clima vs. Tempo): Condições climáticas adversas (como neblina ou chuva forte) impactam o tempo total de entrega de forma mais significativa do que a distância geográfica percorrida.

H2 (Densidade Demográfica): Existe uma correlação forte entre a área de entrega (urbana vs. metropolitana) e a ocorrência de gargalos logísticos.

H3 (Perfil do Entregador): A idade do parceiro de entrega e as avaliações passadas (Agent_Rating) possuem relação causal com a eficiência operacional diária.