# Calculadora-
print ('Olá Amigo!')

nome = input('Como se chama?')

print(f'Seja bem vindo {nome}!')

print('vamos te ajudar no seu dever de Matemática!')

tipo = input('Digite o tipo de conta que voce quer resolver: soma, multiplicação, divisão, divisão inteira e potência: ')
v1 = int(input('Digite aqui o 1 valor: '))
v2 = int(input ('Digite o 2 valor: ' ))

if tipo == 'soma':
    resultado = v1 + v2 
elif tipo == 'multiplicação':
    resultado = v1 * v2
elif tipo == 'divisão':
    resultado = v1 / v2
elif tipo == 'divisão inteira':
    resultado = v1 // v2
elif tipo == 'potência':
    resultado = v1 ** v2 
else:
    print('tipo de conta inválido!')
print(f'o resultado da sua conta è: {resultado}')


print('Encerrando amigo(a)... Até a Proxima conta! ')
