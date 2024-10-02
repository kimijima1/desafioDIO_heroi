#Desafio do herói pela DIO. Autor: kimijima1. Linguagem escolhida: Python
import math
def label():
    if xp<1000:
        print(f"{nome} é ferro")
    elif 1001<xp<2000:
        print(f"{nome} é prata")
    elif 2001<xp<5000:
        print(f"{nome} é prata")
    elif 5001<xp<7000:
        print(f"{nome} é ouro")
    elif 7001<xp<8000:
        print(f"{nome} é platina")
    elif 8001<xp<9000:
        print(f"{nome} é ascendente")
    elif 9001<xp<10000:
        print(f"{nome} é imortal")
    else:
        print(f"{nome} é ascendente")
nome=input("Qual é o nome do seu herói? ")
xp=int(input("Qual é a quantidade de xp do seu herói?"))
classificação=label()
