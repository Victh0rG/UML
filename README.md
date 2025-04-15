# App-de-entrega
Este repositório tem fins didáticos, para a disciplina de UML
App de Entrega de Comida

## Membros

- Victhor Gabriel 
- Vinicius Guimarães 
- Carlos Wagner 
- Pedro Cristóvão 
- João Vitor Gonçalves

## Descrição

Aplicativo de entrega de comida que permite aos usuários realizarem pedidos em diversas lojas, acompanharem o status da entrega em tempo real, e efetuarem pagamentos online de forma segura. Além disso, há funcionalidades para gerenciamento de pedidos e cupons de desconto

## Funcionalidades

- Cadastro e autenticação de usuário
- Login seguro
- Cadastro de endereços (usuário e loja)
- Escolha da forma de pagamento
- Adição e/ou remoção de itens do carrinho
- Uso de cupons de desconto em pedidos
- Confirmação do pedido
- Processamento e confirmação de pagamento
- Notificações sobre status do pedido
- Rastreamento da entrega em tempo real
- Listagem de lojas
- Gestão de pedidos

## Agentes
Cliente(pedido) -> Loja(prepara-pedido) -> entregador(envia-pedido) -> Cliente(recebe-pedido)

## Diagrama Caso de Uso

Demonstra as interações dos usuários (cliente, loja e entregador) com o sistema.

![Image](https://github.com/user-attachments/assets/5fcc089a-da82-4b71-9cb0-d6ab466966d9)

## Diagrama UML

Demonstra a estrutura do sistema e os relacionamentos entre as entidades.

![Image](https://github.com/user-attachments/assets/674a7a2f-fb1c-4440-a7ef-544d223ead88)


## Sistema Bancário

Demonstra as interações dos usuários (cliente, gerente) com o sistema.

## Agentes
Cliente(realiza-transação) → Sistema Bancário(processa-transação) →
Gerente(aprova-ou-bloqueia) → Sistema Bancário(executa) →
Sistema Externo(processa-pagamento) → Sistema Bancário(retorna-status) →
Cliente(recebe-confirmação)

![Image](https://github.com/user-attachments/assets/43640e95-0214-4a13-8306-f07850c54f0f)

![Image](https://github.com/user-attachments/assets/dc5408a7-fef0-4e13-a192-f300042ab646)

![Image](https://github.com/user-attachments/assets/631dc247-cfcb-4750-84e4-2c5bff399993)


## Biblioteca

Demonstra as interações dos usuários (cliente, gerente) com o sistema.

## Agentes
Usuário(solicita-empréstimo) → Sistema(autentica-usuário) →
Usuário(reserva-livro) → Sistema de Notificação(envia-confirmação-de-reserva) →
Bibliotecário(registra-devolução) → Sistema de Notificação(envia-notificação-pendente) →
Sistema de Notificação(envia-alerta-de-livro-disponível) → Usuário(recebe-alerta)

![Image](https://github.com/user-attachments/assets/c4d8d089-b10c-4b26-afdb-fa29ab145632)

![Image](https://github.com/user-attachments/assets/8b8502c6-f5c0-4de3-9263-73ab55c05e48)

## Loja Online

##Agentes
Cliente(faz-login) → Sistema(autentica-usuário) →
Cliente(busca-produto) → Sistema(exibe-produtos) →
Cliente(adiciona-ao-carrinho) → Sistema(registra-itens) →
Cliente(finaliza-compra) → Sistema de Pagamento(processa-pagamento) →
Sistema(emite-recibo) → Cliente(acompanha-pedido)
⠀
Administrador(faz-login) → Sistema(valida-acesso) →
Administrador(cadastra-produto | gerencia-estoque)




## <h1>Membros</h1>

- <h2>Victhor Gabriel</h2> 
- <h2>Vinicius Guimarães</h2>   
- <h2>João Vitor Gonçalves</h2>

