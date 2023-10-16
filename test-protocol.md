Protocolos para separação de dados entre Treino e Teste pro dataset PKLot

Protocolo 1:
- Em um mesmo estacionamento, dados pertencentes a um mesmo dia não podem pertencer a um conjunto de teste e treino ao mesmo tempo.
- Dividir 50% para teste e 50% para treino tendo isso em mente
- Para os testes nesse trabalho, 116 instâncias do dataset de Teste são selecionadas de forma randômica, a fim de diminuir o tempo de execução.
- Estacionamento escolhido é o UFPR04

Disposições gerais dos testes:

Foram implementadas duas versões do classificador knn. Uma utilizando a biblioteca sklearn e outra implementada de forma manual.
Para cada protocolo, serão realizados os testes nas duas versões.
Serão realizados testes com:
- k = 2
- k = 3
- k = 6


Protocolo 2:
- Os dados pertencentes ao estacionamento da UFPR(1000 + 1000 imagens) serão usadas para treinamento. Imagens selecionadas de forma randômica;
- Os dados pertencentes a PUC(100 imagens) serão usadas para teste. Imagens selecionadas de forma randômica;