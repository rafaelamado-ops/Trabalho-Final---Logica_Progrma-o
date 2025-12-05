# Trabalho-Final---Logica_Progrma-o

var
   estoque: vetor[1..50] de inteiro
   nomesProdutos: vetor[1..50] de caractere
   precoProdutos: vetor[1..50] de real
   totalProdutos: inteiro
   nome, email, telefone: caractere
   historicoCompras: vetor[1..100] de caractere
   totalCompras: inteiro
   datadecadastro: inteiro
   senha2: caractere
   login, senha: caractere
   usuarioAutenticado: logico
   rua, numero, complemento:caractere
   bairro, cidade, cep: caractere
   opcao: inteiro
   valor: real



inicio
   totalProdutos <- totalProdutos + 1
   escreva("Nome do produto: ")
   leia(nomesProdutos[totalProdutos])
   escreva("Preço: R$ ")
   leia(precoProdutos[totalProdutos])
   escreva("Estoque: ")
   leia(estoque[totalProdutos])
   escreval("Produto cadastrado com sucesso!")
   escreval

   escreva("Nome do Cliente: ")
   leia(nome)
   escreva("Email do Cliente: ")
   leia(email)
   escreva("Telefone do Cliente: ")
   leia(telefone)
   escreval("senha do Cliente")
   leia(senha)
   escreval("Data de Cadastro")
   leia(datadecadastro)
   escreval("Cliente cadastrado com sucesso!")
   escreval
   
   escreva("Login: ")
   leia(login)
   escreva("Senha: ")
   leia(senha2)


   se (login = "admin") e (senha2 = "123") entao
      usuarioAutenticado <- verdadeiro
      escreval("Usuário autenticado com sucesso!")
   senao
      usuarioAutenticado <- falso
      escreval("Falha na autenticação!")
   fimse


   usuarioAutenticado <- falso
   escreval("Logout realizado com sucesso!")
   escreval
   
   escreva("Rua: ")
   leia(rua)
   escreva("Número: ")
   leia(numero)
   escreva("Complemento: ")
   leia(complemento)
   escreva("Bairro: ")
   leia(bairro)
   escreva("Cidade: ")
   leia(cidade)
   escreva("CEP: ")
   leia(cep)
   escreval("Endereço cadastrado com sucesso!")
   escreval
   
   escreva("Digite o valor total: R$ ")
   leia(valor)
   escreval("Forma de pagamento:")
   escreval("1 - dinheiro ")
   escreval("2 - Cartão")
   escreval("3 - Pix")
   escreva("Opção: ")
   leia(opcao)

   escreval("")
   escreval("")
   escreval("Valor total: R$ ", valor)
   
   fimalgoritmo
