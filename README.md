# Grupo de Estudos sobre Lógica de Programação
Repositório destinado para exercícios sobre Programação.

1. Escrever um programa que lê 8 números reais e armazena esses valores em um array (vetor). O programa deve calcular a média aritmética dos valores do vetor e imprimir todos os valores menores que a média calculada.

```
Algoritmo "questao1"
Var
array: vetor[1..8] de real
i: inteiro
soma, media: real
Inicio
Para i de 1 ate 8 faca
   Escreva ("Digite o ",i," valor: ")
   Leia (array[i])
   soma:=soma+array[i]
fimpara

media:=soma/i
Escreval ("A media é: ", media)
Escreval ("Os valores menores do que a média são: ")

Para i de 1 ate 8 faca
   Se (array[i] < media) entao
      Escreva (array[i])
   fimse
fimpara

Fimalgoritmo
```

2. Calcular e mostrar a média aritmética dos números pares compreendidos entre 13 e 73.
```
Algoritmo "questao2"
Var
i, soma, cont: inteiro
media: real
Inicio
para i de 13 ate 73 faca
     se i mod 2 = 0 entao
        soma:= soma+i
        cont:= cont+1
     fimse
fimpara
media:= soma/cont
escreva("A média é: ", media)
Fimalgoritmo
```

3. Ler três valores e determinar o maior dentre eles.
```
Algoritmo "questao3"
Var
a, b, c, maior: inteiro
Inicio
escreva("Digite o primeiro valor: ")
leia(a)
escreva("Digite o segundo valor: ")
leia(b)
escreva("Digite o terceiro valor: ")
leia(c)
maior:= a
se b > maior entao
   maior:= b
fimse
se c > maior entao
   maior:= c
fimse
escreva("O maior valor digitado é:", maior)
Fimalgoritmo
```

4. Dada uma sequência de 5 números inteiros, imprima na ordem inversa à de leitura.
