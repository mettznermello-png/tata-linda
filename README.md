# tata
algoritmo "Exercicio 1"

var
  lerVetor: vetor[1..5] de inteiro;

inicio

  leia(lerVetor[1])
  leia(lerVetor[2])
  leia(lerVetor[3])
  leia(lerVetor[4])
  leia(lerVetor[5])

  escreva(lerVetor[1])
  escreva(lerVetor[2])
  escreva(lerVetor[3])
  escreva(lerVetor[4])
  escreva(lerVetor[5])

fimalgoritmo


##Exercicios

```bash

inicio

var
inteiro A[5][3], B[5][3], C[5][3]
inteiro n, x

para n de 1 ate 5 faca
   para x de 1 ate 3 faca
      escreva("Digite A[", n, "][", x, "]: ")
      leia(A[n][x])
   fimpara
fimpara
para n de 1 ate 5 faca
   para x de 1 ate 3 faca
      escreva("Digite B[", n, "][", x, "]: ")
      leia(B[n][x])
   fimpara
fimpara

para n de 1 ate 5 faca
   para x de 1 ate 3 faca
      C[n][x] <- A[n][x] + B[n][x]
   fimpara
fimpara
escreval("Matriz C (resultado):")
para n de 1 ate 5 faca
   para x de 1 ate 3 faca
      escreva(C[n][x], " ")
   fimpara
   escreval("")
fimpara

fimalgoritmo
```

```bash
inicio

inteiro A[7], B[7]
inteiro C[7][2]
inteiro n
para n de 1 ate 7 faca
   escreva("Digite A[", n, "]: ")
   leia(A[n])
fimpara
para n de 1 ate 7 faca
   escreva("Digite B[", n, "]: ")
   leia(B[n])
fimpara
para n de 1 ate 7 faca
   C[n][1] <- A[n]
   C[n][2] <- B[n]
fimpara
escreval("Matriz C:")
para n de 1 ate 7 faca
   escreval(C[n][1], " ", C[n][2])
fimpara

fimalgoritmo
```