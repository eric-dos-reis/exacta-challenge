# Exacta-challenge

## Regras gerais

Serão consideradas funcionalidades completas se:

- O descritivo da funcionalidade for implementado completamente
- A tela estiver aderente ao protótipo
- Não houver bugs que atrapalhem ou impossibilitem a execução da funcionalidade

Serão considerados bônus:

- Teste unitário
- Teste de UI
- README.md bem escrito com um passo a passo para que seja possível executar o projeto

## Funcionalidades

Marque os checkbox conforme for concluindo as tarefas

### Marketplace

**Eu como** usuário

**Gostaria de** acessar o app

**e** navegar por todos os produtos

Critérios de aceite

- [ ] Listar todos os produtos que a API retorna
- [ ] Filtrar produtos por nome
- [ ] Filtrar produtos por categoria
- [ ] Ordenar produtos por preço (crescente ou decrescente)
- [ ] Salvar produtos no carrinho conforme clicar em adicionar os produtos

### Carrinho de compra

**Eu como** usuário

**Gostaria de** acessar meu carrinho de compra

**e** ver todos os produtos que eu adicionei via marketplace

Critérios de aceite

- [ ] Listar todos os produtos adicionados no carrinho
- [ ] Possibilitar acrescentar ou diminuir a quantidade do produto
- [ ] Possibilidade de excluir produtos do carrinho

### Fluxo de cadastro

**Eu como** usuário

**Gostaria de** criar minha conta

**Afim de** poder comprar produtos no app

Critérios de aceite

- [ ] Entrar no fluxo de cadastro pela botão "Criar conta" na tela de Login
- [ ] Conseguir ver os produtos adicionados no carrinho em um component accordion
- [ ] No campo de data usar o seletor de data padrão do sistema operacional
- [ ] Validação de cpf
- [ ] Validar se o e-mail informado está num formato válido
- [ ] Usar máscara de telefone (99) 99999-9999
- [ ] Todos os campos com asterisco (\*) são obrigatórios
- [ ] Ao clicar em continuar a compra, deverá validar se todos os campos estão válidos, caso contrário apresentar uma mensagem de erro embaixo de cada campo com a respectiva mensagem de erro
- [ ] No campo de CEP usar uma API de CEP (por exemplo: https://viacep.com.br/) para preencher os campos relacionados ao endereço
- [ ] Caso a API der timeout liberar o preenchimento dos campos de forma manual

### Fluxo de compra

**Eu como** usuário

**Gostaria de** finalizar minha compra

**para que** consiga pagar e receber meus produtos

Critérios de aceite

- [ ] Ao clicar em cartão mostrar as opções de cadastro de cartão e parcelamento
- [ ] Dar a opção do cliente parcelar sua compra em até 3x sem juros
- [ ] Dar a opção do cliente parcelar sua compra de 4 a 6x com um adicional de 7% no valor total
- [ ] Validar campos ao clicar em finalizar a compra
- [ ] Mostrar tela de sucesso após concluir uma compra com sucesso

### Protótipo navegável e assets

O assets estão na pasta [assets](./assets) do repositório e o protótipo navegável pode ser acessado por este [link](https://www.figma.com/proto/FaaAwc3nRRW4cTuxlQPNxw/Bicycle-Shop?node-id=118%3A280&scaling=min-zoom)

## Especificações

### Particularidades do desafio Android

- Mínimo SDK: API 15
- Linguagem: Java ou Kotlin

### Particularidades do desafio iOS:

- Versão mínima: iOS 9
- Linguagem: Swift

### Particularidades do desafio React Native

- Versão mínima: latest
