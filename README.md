# Projeto_Bank

- Parte 1:
- Pensando em exercitar os conceitos estudados de criação de atributos privados, construtores, sobrecarga de métodos, encapsulamento e criação de getters e setters.
- Foi proposto um exercício com enfâse em um sistema bancário, o exemplo feito realiza leitura de um número de conta que não pode ser alterado pois realizamos a criação dos atributos privados e na criação dos getters e setters definimos a ele apenas o get.
- Em seguida o sistema solicita ao usuário que seja digitado o nome da pessoa no qual estamos realizando o cadastramento no mesmo, esse atributo também foi criado privado, o nome pode ser alterado como por exemplo: uma pessoa se cada o nome dela pode ser alterado ou não, então por esse mótivo definimos um getHolder e setHolder para termos acesso a fazer alterações se possível.
- O proximo passo é verificar junto a criação se será depositado algum valor na conta ou não, dependendo da opção desejada o sistema tera uma ação adequada a escolha.

- Parte 2:
- Criamos um metódo que realiza um deposito na conta do cliente, então é solicitado um valor para que a transação seja feita com sucesso.
- Criamos também um outro metódo que realiza o saque mas com uma regra bastante importante do banco, a cada saque é descontado da conta do cliente R$ 5.00, não importa se o saldo do mesmo irá se manter positivo ou não.
