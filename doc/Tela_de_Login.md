# Tela de Login

### Objetivos

O objetivo da funcionalidade é permitir que o usuário faça login no sistema. A tela deverá validar campos obrigatórios, inputs e retornar erros e mensagens ao usuário conforme descrito nesta documentação.

### Protótipo

N/A (link para um protótipo do Figma estaria aqui). Nesse caso, colocarei apenas um print da tela final:

![Tela Final](/doc/final.png)


### Requisitos

1. O sistema deve permitir que o usuário faça login no painel do jogador;
2. Deve ser exibido um input para que o usuário insira o e-mail de acesso;
3. O input de e-mail será de preenchimento obrigatório;
4. Deve ser exibido um input para que o usuário insira a senha de acesso;
5. O input de senha será de preenchimento obrigatório;
6. O input de senha deverá mascarar a senha digitada pelo usuário;
7. Deve ser exibido um checkbox para que o usuário salve a senha;
8. O checkbox de salvar a senha deverá vir desmarcado por padrão;
9. Um link deverá ser exibido para que o usuário recupere a senha de acesso;
10. Um botão deve ser exibido para realizar o acesso ao painel;
11. Deve ser exibida a opção de cadastro no painel;

### Regras de Negócio

1. Ao clicar em "Esqueci minha senha" o sistema deverá direcionar o usuário para a tela de recuperação de senha que seguirá o definido em [documentação própria -- *em criação*](#).
2. Ao clicar no botão ACESSAR:
    1. Caso o usuário não tenha digitado o e-mail de acesso, o sistema não deverá prosseguir e deve exibir em uma tooltip no input de e-mail a mensagem: "Preencha este campo";
    2. Caso o usuário tenha informado o e-mail, mas não tenha digitado a senha de acesso, o sistema não deverá prosseguir e deve exibir em uma tooltip no input de e-mail a mensagem: "Preencha este campo";
3. Ao clicar em "Cadastre-se" o sistema deverá direcionar o usuário para a tela de cadastro, a qual seguirá o definido em [documentação própria -- *em criação*](#).