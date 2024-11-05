def soma_matrizes(A, B):
    # assumindo que A e B têm as mesmas dimensões
    linha = len(A)
    colunas = len(A[0])
c = [[0 for _ in range(colunas)] for _ in range(linhas)]

for i in range(linhas):
    for j in range(colunas):
        c[i][j] = A[i][j] + B[i][j]
