TREINAMENTO SUPERVISIONADO.

Algoritimo de aprendizagem perceptron de uma única camada regra delta, processo adeline.

(w,j)T + i  = valor do peso corrigido.
(w,j)T =  valor do peso na interação anterior.
E(j) T = valor do erro para o neuronio j.
i = indice do sinal de entrada.
T = interação.
j = indice do reunocio.
n = taxa de aprendizado.
x(i) = sinal de saida.

(E)j Diferença do sinal da saida a o resultado esperado:
E(j)=d(j)- y(j).



+----------+-------------+--------------+
|vermelho__|_____1_______|______________|
|amarelo___|_____0_______|______________|
|verde     |             |      0       |
+----------+-------------+--------------+


vermelho = 1
amarelo = 1
verde = -1

Função de Ativação:

v = 0x1 + 0x1 + 0x1 =0

Funcão de transferencia:
corrigir:
E= 1 - 0 = 1

w1 = 0 + 1 x 1 x 1 = 1;
w2 = 0 + 1 x 1 x 1 = 1;
b  = 0 + 1 x 1 x 1 = 1.

Iniciando o reconhecimento :

Função de Ativação:
v = 1x0 +1 x1 + 0x0 = 1
funcao transferencia:
correção:
E= 1 - 1 = 0

w1 = 1 + 1 x (0) x 1 = 1;
w2 = 0 + 1 x (0) x 1 = 0;
b = 0 + 1 x (0) x 1 = 0.

