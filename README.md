# Random number
Algoritmo em python que desafia o usuário acertar um número aleatório entre 1 à 10.

# Adivinhe o número aleatório usando a função while
```bash
import random
x = 0
num = random.randint(1,10)
sugestao = int(input("Tenta adivinhar um número de 1 à 20000: "))

while sugestao != num:
    if sugestao > num:
        print("O número é menor!")
    elif sugestao < num:
        print("O número é maior!")
    x = x + 1
    print(f"tentativas: {x}")
    sugestao = int(input("Tente novamente: "))

print(f"Você acertou em {x} tentativas, parabéns!😀")
```
