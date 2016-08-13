# Estrutura-De-Repeti-o
Estrutura de Repetição - Questões 26 á 34

P4.26
Permite que uma sequência de comandos seja executados repetidamente enquanto uma determinada condição seja satisfeita.

P4.27
Quando for previamente conhecido o número de repetições, usamos o contador para controlar o número de repetições do laço.

P4.28 
Quando o número de repetições não se é conhecido e este for determinado por um valor que será lido, utilizamos o controle de
repetição por entrada (FLAG).

P4.29

N	L	N # 6		saída 
0	-1	verdadeiro		
1	 1	verdadeiro	1
2	-1	verdadeiro	
3	 1	verdadeiro	3
4	-1	verdadeiro	
5	 1	verdadeiro	5
6	-1	falso

P4.30 
N = 1
while(N <= 50):
    print(N)
    N = N + 1

P4.31 
N = 1
while(N <= 100):
    N = N + 1
    if(N % 2 == 0):
        print(N)

P4.32 
N = 10
while(N <= 1000):
    print(N)
    N = N + 10

P4.33
N = 100
while(N >= 1 and N <= 100):
    print(N)
    N = N - 1

P4.34
N = int(input("Insira um número:"))

Ninicial = 1
Nfinal = 0

while (Ninicial <= N):
    Nfinal = Nfinal + Ninicial
    Ninicial = Ninicial + 1

print(Nfinal)  
