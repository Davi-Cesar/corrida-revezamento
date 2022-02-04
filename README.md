# Corrida-revezamento
Um programa em Go que simule uma corrida de revezamento em que uma equipe possui
quatro corredores. O segundo, terceiro e quarto corredores não podem começar a correr até que
recebam o bastão entregue pelo corredor que o antecedeu. Para simular a corrida do corredor na
etapa em questão, pode-se utilizar o método Sleep provido pelo pacote time por um intervalo de
tempo predefinido. O bastão deve ser passado para o próximo corredor até que o último corredor
conclua o trecho a ser percorrido, momento em que o programa deverá ser encerrado. Por questões de
simplicidade, desconsidere as regras válidas no mundo real em que o bastão necessita ser entregue nos
20 metros finais de cada etapa a ser percorrida.

# Extra
Modifique o programa implementado para que haja mais de uma equipe de atletas participando
da corrida de revezamento, cada uma em uma raia, de forma similar ao que ocorre no mundo real. Ao
término de sua execução, o programa deverá informar qual das equipes venceu a prova.
