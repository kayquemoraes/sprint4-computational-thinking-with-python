# Sistema de Reciclagem EcoSort

Este é um sistema de reciclagem simples chamado EcoSort, que permite aos usuários depositar resíduos em uma lixeira inteligente e receber recompensas com base nos materiais reciclados. O código está escrito em Python e utiliza armazenamento em arquivo JSON para persistência de dados.

## Funcionalidades Principais

### 1. Armazenamento de Dados
O programa utiliza um arquivo chamado `banco.txt` para armazenar informações sobre usuários e materiais em formato JSON. As informações são carregadas no início do programa e atualizadas durante a execução.

### 2. Autenticação de Usuário
Os usuários podem se registrar ou fazer login usando um nome de usuário e senha. Caso um usuário não exista, ele pode se registrar. A senha é armazenada de forma segura.

### 3. Depósito de Resíduos
Os usuários podem depositar resíduos na lixeira inteligente fornecendo o código de barras do produto. A quantidade do resíduo é registrada, e um cupom é gerado com informações sobre os resíduos depositados.

### 4. Consulta e Cadastro de Produtos
Os usuários podem consultar se um produto está registrado no sistema e, se não estiver, têm a opção de cadastrá-lo. A composição do produto (plástico, metal, vidro, papel) é escolhida durante o cadastro.

### 5. Consulta de Saldo
Os usuários podem verificar seu saldo, que é atualizado com base nos resíduos depositados.

### 6. Informações sobre a Lixeira Inteligente
Os usuários podem obter informações sobre como a lixeira inteligente funciona, incluindo o reconhecimento de materiais e o sistema de recompensas.

## Exemplo de Execução

Aqui está um exemplo simulado de como o EcoSort pode ser usado:

```python
[1] Entrar
[2] Registrar
Digite: 2

Nome de usuário: novo_usuario
Senha: nova_senha
Registro bem-sucedido!

[1] Depositar um resíduo na lixeira
[2] Consultar ou cadastrar um produto
[3] Consultar seu saldo
[4] Conhecer nossa lixeira
[5] Encerrar sua sessão
Digite: 1

Digite o código de barras do produto a ser descartado: 000a
Digite a quantidade deste resíduo: 3
Resíduo depositado com sucesso!

[1] Depositar um resíduo na lixeira
[2] Consultar ou cadastrar um produto
[3] Consultar seu saldo
[4] Conhecer nossa lixeira
[5] Encerrar sua sessão
Digite: 3

Seu saldo é: 15

[1] Depositar um resíduo na lixeira
[2] Consultar ou cadastrar um produto
[3] Consultar seu saldo
[4] Conhecer nossa lixeira
[5] Encerrar sua sessão
Digite: 5

Obrigado por usar nossa lixeira!
nome de usuario : novo_usuario
plastico: 3
valor total : 15

```

## Contribuição

Sinta-se à vontade para contribuir com melhorias neste projeto. Você pode adicionar recursos adicionais, aprimorar a interface do usuário ou fazer correções de bugs.

Esperamos que o EcoSort seja útil para promover a reciclagem e a conscientização ambiental. Faça a sua parte e seja recompensado por suas ações sustentáveis!