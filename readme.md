## Desafio Woovi - Crud Bank GraphQL Relay
A Woovi é uma startup que oferece soluções no topo de pagamentos como Pix e Cartão de Crédito.

Atualmente temos dois produtos: Woovi e OpenPix

Woovi
OpenPix

## Desafio
Nosso desafio replica nosso dia-a-dia. Consiste na construção de um CRUD de um banco baseado em nossas tecnologias.

Além da tecnologia, o desafio leva você à imersão na rotina de trabalho em uma startup. Ao falar de startup, entenda que somos uma porque estamos construindo algo novo e sem definições previamente definidas por outras pessoas. Então nossa rotina é codificar de maneira razoavelmente boa. Mas mais do que isso, desbloqueando o negócio e tomando a melhor decisão para entregar o que o cliente precisa.

## Stack do Desafio
Stack - https://dev.to/woovi/woovi-stack-5fom
Backend: MongoDB, NodeJS, Koajs, GraphQL
Frontend: React, Relay
Testes: Jest
Backend
O backend deve ser uma API GraphQL que manipula todos os itens necessários mencionados acima.

Stack: NodeJs, KoaJs, MongoDB, GraphQL

Além disso: Use Node e Connection do Relay para lidar com coleções e listas.

Mutations de Login e Registro
Deve haver uma Mutation disponível para registrar um novo usuário.
Esta mutation deve retornar o usuário logado com sucesso.
Deve estar disponível como Mutation para fazer login como usuário.
Deve lidar com autenticação de token para o login.
Deve persistir o token entre requisições.
Deve criar o token com autenticação JWT.
O token deve ser transferido por ...
Deve criar um usuário com uma conta

## Modelo de Usuário
Deve ter um primeiro nome, CPF (campo de CPF/CNPJ) e senha.
A senha deve ser criptografada.
Não deve ser possível registrar mais de um usuário com o mesmo CPF.

## Modelo de Conta
ID único a ser usado como ID de idempotência.
Número da conta.
ID do usuário proprietário da conta.
Deve ser capaz de ter uma conta por usuário.
Não deve ser possível duplicar contas.
Deve ter o cálculo do saldo usando uma estratégia de livro-razão.

## Modelo de Transação
Remetente: quem está enviando o dinheiro
Destinatário: quem está recebendo o dinheiro
Deve ser idempotente
Valor: em centavos ou decimal128

## Deploy
O backend deve ser implantado onde pode ser acessado.
Como garantir uma melhor chance de ser contratado pelo backend?
Exponha um Playground GraphQL
Gere um JSON do postman para poder importar e fazer chamadas para a API GraphQL do Backend
Use graphql-HTTP
Tenha um teste com Jest ou um Test Runner de escolha
