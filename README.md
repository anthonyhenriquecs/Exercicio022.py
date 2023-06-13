# Exercicio022.py
#Crie um programa que leia o nome completo de uma pessoa e mostre: – O nome com todas as letras maiúsculas e minúsculas. – Quantas letras ao todo (sem considerar espaços). – Quantas letras tem o primeiro nome.

nome = str(input('Digite seu nome: ')).strip()
print(nome.upper(),nome.lower())
print(len(nome)-nome.count(' '))
#print(nome.find(' '))
separado = nome.split()
print('seu primeiro nome é {} e tem {} letras'.format(separado[0], len(separado[0])))
