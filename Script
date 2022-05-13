''' 
Quando rodar o código isso é o que aparece inicialmente na tela para o usuário.
'''


print("\n******************* Calculadora Python *******************")
print("\n")
print('Selecione o número da operação desejada: \n\n 1 - Soma \n 2 - Subtração \n 3 - Multiplicação \n 4 - Divisão')


'''
Aqui são criadas as variáveis e atribuídas a elas a função input que abre opção para entrada de dados,
já os convertendo para int, pois entram como str.
No caso aqui serão as opções 1, 2, 3 ou 4.
'''


operação = int(input('\nDigite sua opção (1/2/3/4): '))
fstNum = int(input('\nDigite o primeiro número: '))
sndNum = int(input('\nDigite o segundo número: '))


'''
Aqui foram delimitadas as condições.
Se a entrada dor primeiro input for 1, será feita uma soma com o segundo e terceiro input (fstNum e sndNum).
Se a entrada for '2', será feita uma subtração, se for '3' multiplicação, se '4', divisão.
'''


if operação == 1:
    print("\n")
    print(fstNum, "+", sndNum, "=", (fstNum + sndNum))

elif operação == 2:
    print("\n")
    print(fstNum, "-", sndNum, "=", (fstNum - sndNum))

elif operação == 3:
    print("\n")
    print(fstNum, "*", sndNum, "=", (fstNum * sndNum))

elif operação == 4:
    print("\n")
    print(fstNum, "/", sndNum, "=", (fstNum / sndNum))


'''
Caso as condições acima não forem atendidas, ou seja,
caso a primeira entrada seja diferente de 1, 2, 3 ou 4, a seguinte mensagem de erro aparece.
'''


else:
    print('\nOpção Inválida!')
