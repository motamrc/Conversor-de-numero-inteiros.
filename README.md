numero = int(input('Digite um numero: '))
print('''Escolha uma opcao:
[ 1 ] converter para BINARIO.
[ 2 ] converter para OCTAL
[ 3 ] converter para HEXADECIMAL
[ 0 ] sair. ''')
numero_escolhido = int(input('numero escolhido: '))

if numero_escolhido == 1:
    print(f'{numero} convertido para binario eh igual a {bin(numero)[2:]}.')

elif numero_escolhido == 2:
    print(f'{numero} convertido para octal eh igual a {oct(numero)[2:]}')

elif numero_escolhido == 3:
    print(f'{numero} convertido para hexadecimal eh igual a {hex(numero)[2:]}')

elif numero_escolhido == 0:
    print('Saindo...')

else:
    print('Numero incorreto, escolha uma das 3 opcoes.')
