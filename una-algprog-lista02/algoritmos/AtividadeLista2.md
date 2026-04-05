**O Caixa Eletrônico**



Alogritmo Saque 



Inicio VAR 



valor\_saque : real

saldo\_disponivel : real



Fim VAR 



Escreva (Informe valor do saque:)

Leia valor\_saque



Se valor\_saque <= saldo\_disponivel entao

saldo\_disponivel <- saldo\_disponivel - valor\_saque

Escreva (Notas entregues)



Senão Escreva (Saldo Insuficiente)

FimSE 



Fim algoritmo





**Media Aluno**



Algoritmo "Validador\_de\_Notas"

Var

&#x20;   nota: real

Inicio

&#x20;   Escreva("Informe a nota final: ")

&#x20;   Leia(nota)



&#x20;   Se (nota >= 7.0) entao

&#x20;       Escreva("Status: APROVADO")

&#x20;   Senao

&#x20;       Escreva("Status: EXAME FINAL")

&#x20;   FimSe

&#x20;   

FimAlgoritmo

