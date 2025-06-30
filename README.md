# Praticando_Python
#Peça ao usuário para digitar seu nome
#Peça ao usuário para digitar sua idade
#Se nome e idade forem digitados:
    #Exiba:
     #   Seu nome é {nome}
      #  Seu nome invertido é {nome invertido}
        #Seu nome contém (ou não) espaços
       #Seu nome tem {n} letras
        #A primeira letra do seu nome é {letra}
       # A última letra do seu nome é {letra}
#Se nada for digitado em nome ou idade: 
    #exiba "Desculpe, você deixou campos vazios."

nomeUsuario = input('Digite o seu nome de usuario')
idadeUsuario_str = input('Digite a idade do usuario')

if nomeUsuario.strip() and idadeUsuario_str.strip():
  idadeUsuario = int(idadeUsuario_str)
  nomeInvertido = nomeUsuario[::-1]
  totalLetras= len(nomeUsuario)
  EspaçoNome = " " in nomeUsuario
  NinNome= "n" in nomeUsuario
  primeiraLetra = nomeUsuario[0]
  ultimaLetra = nomeUsuario[-1]

  print(f'O nome do usuario é :{nomeUsuario} que invertido ficaria {nomeInvertido}')
  print(f'A idade dele é:{idadeUsuario}')
  print(f'o nome contem espaço é :{EspaçoNome} e letra não é: {NinNome}')
  print(f'A primera letra do nome do usaario é :{primeiraLetra}')
  print(f'E a ultima letra é:{ultimaLetra}') 
else: 
  print('Desculpe,voce deixo campos vazios')
Praticando em python
