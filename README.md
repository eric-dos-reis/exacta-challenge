# Exacta-challenge

## Regras gerais

### Serão consideradas funcionalidades completas se:

O descritivo da funcionalidade for implementado completamente.  
A tela estiver aderente ao protótipo.  
Não houver bugs impeditivos que atrapalhem ou impossibilitem a execução da funcionalidade.  
O layout estiver aderente à todos os devices que suportem a versão mínima e superiores.

### Serão considerados bônus:

Teste unitário  
Teste de UI  
Caso seu projeto possua alguma pré condição para ser executado, crie um arquivo README.md com um passo a passo para que seja possível executá-lo.

_Foque em entregar funcionalidades completas!_

## Funcionalidades

### Fluxo de login

**Eu como** usuário

**Gostaria de** acessar o app

**Com as credenciais**:
user: admin@admin.com
senha: admin

Critérios de aceite

- [x] Ao clicar em entrar deverá validar máscara de email
- [x] Ao sair do campo de email deverá ser validado a máscara de email
- [x] O erro deverá ser renderizado em uma modal com a frase "O email inserido está errado"
- [x] Todo o layout deverá seguir o template de exemplo
- [x] Após clicar em entrar manter uma sessão do usuário até que ele feche o aplicativo

### Fluxo de cadastro

**Eu como** usuário

**Gostaria de** criar minha conta

**Afim de** poder comprar produtos no app

Critérios de aceite

- [x] Conseguir ver detalhes no dropdown dos produtos já escolhido no marketplace
- [x] Validar campos após sair dos mesmos e caso esteja inválido mudar o contorno do campo para vermelho
- [x] Validar campos após sair dos mesmos e caso esteja válido mudar o contorno do campo para verde
- [x] Validar campo de nome e sobrenome para não serem maiores que 50 caracteres e somente letras
- [x] No campo de data usar o seletor de data padrão do sistema operacional
- [x] Usar um algoritmo para validação de cpf (exemplo: http://www.receita.fazenda.gov.br/aplicacoes/atcta/cpf/funcoes.js) e deixar inserir apenas números
- [x] O campo email estar sendo validado
- [x] Usar máscara de telefone (99) 99999-9999
- [x] Exceto o campo telefone secundário, todos os outros campos são obrigatórios
- [x] Ao clicar em continuar a compra deverá validar se todos os campos estão preenchidos e válidos, caso tenha algum problema deverá mostrar a modal de erro com os dizeres "Verifique os campos incorretos"
- [x] Caso a api der timeout liberar o preenchimento dos campos de forma manual
- [x] No campo de CEP usar a api: https://viacep.com.br/ para preencher os campos e usar um loading para a espera da resposta da api

### Fluxo de compra

**Eu como** usuário

**Gostaria de** finalizar minha compra

**para que** consiga pagar e receber meu item

Critérios de aceite

- [x] Ao clicar em cartão mostrar as opções de cadastro de cartão e parcelamento
- [x] Dar a opção do cliente parcelar sua compra em até 3x sem juros
- [x] Dar a opção do cliente parcelar sua compra de 4 a 6x com um adicional de 7% no valor total
- [x] Validar campos ao clicar em finalizar a compra
- [x] Mostrar tela de sucesso após concluir uma compra com sucesso

### Marketplace

**Eu como** usuário

**Gostaria de** acessar o app

**e** navegar por todos os produtos

Critérios de aceite

- [x] Listar todos os produtos que a api retorna
- [x] Conseguir buscar produtos por título
- [x] Conseguir filtrar produtos por categoria
- [x] Conseguir ordenar produtos por preço (crescente e decrescente)
- [x] Salvar produtos no carrinho conforme clicar em adicionar os produtos

### Carrinho de compra

**Eu como** usuário

**Gostaria de** meu carrinho de compra

**e** ver todos os produtos que eu adicionei via marketplace

Critérios de aceite

- [x] Listar todos os produtos adicionados no carrinho
- [x] Possibilitar adicionar mais do mesmo produto
- [x] Possiblidade de remover produtos
- [x] Possibilidade de excluir produtos do carrinho
- [x] Ao continuar a compra se o usuário não estiver logado enviar para a tela de login

## Especificações

- [Android.md](Android.md)
- [IOS.md](IOS.md)
- [React-native.md](React-native.md)
