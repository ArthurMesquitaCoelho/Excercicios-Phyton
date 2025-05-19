estabelecimentos = []

def exibir_opçoes():
    print('\n' + '='*30)
    print('*********FOOD COMPANY*****')
    print('='*30)
    print('1. Cadastrar restaurante')
    print('2. Listar restaurante')
    print('3. Remover restaurante')
    print('4. Sair\n')

exibir_opçoes()

def cadastrar():
    for i in range(3):
       restaurante_add = input ('Digite o restaurante que deseja adicionar: ')
       estabelecimentos.append(restaurante_add)

def remover():
    nome = input('Digite o restaurante que deseja remover')
    if nome in estabelecimentos:
        estabelecimentos.remove(nome)
        print(f'Restaurante''{nome}''removido com sucesso')
    else:
        print(f'Restaurante''{nome}' 'não consta na lista')
    
while True:
    exibir_opçoes()
    opcao = int(input('Digite a opção desejada: '))

    if opcao == 1:
        cadastrar()

    elif opcao == 2:
        print(estabelecimentos)

    elif opcao == 3:
        print(estabelecimentos)
        remover()
    elif opcao == 4:
        print('Obrigada por utilizar nosso app volte sempre!')
