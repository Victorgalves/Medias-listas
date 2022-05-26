from time import sleep
total=[]
notas=[]
parar=0
while True:
    nome=input('Digite seu nome: ')
    n1=int(input('Nota 1: '))
    n2=int(input('Nota 2: '))
    total.append(nome)
    total.append(n1)
    total.append(n2)
    notas.append(total[:])
    total.clear()
    continuar= input('Deseja continuar? [S/N]: ')
    if continuar in 'nN':
        break
print('Calculando as médias...')
sleep(1)
print(f"{'=-'*60:>15}")
print(f'{"No.":>15}',end='')
print(f'{"Nome":>15}',end='')
print(f'{"Média":>15}')
print(f'{"-" * 50:>15}')
for c,n in enumerate(notas):
    ma=(n[1]+n[2])/2
    print(f'{c:>15}',end='')
    print(f'{n[0]:>15}',end='')
    print(f'{ma:>15}')
while True:
    mostrar=int(input('Deseja mostrar a nota de qual aluno? se quiser parar, digite 999: '))
    if mostrar==999:
        print('FINALIZANDO....')
        sleep(0.5)
        print('Obrigado por utilizar o programa!')
        break
    for i in range(0,len(notas[0])):
        nota1=notas[i][1]
        nota2=notas[i][2]
        if mostrar==i:
            print(f'{nota1} e {nota2}')
    
    