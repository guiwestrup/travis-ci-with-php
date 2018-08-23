# Como usar TRAVIS-CI

## O que é o TRAVIS-CI?
O TRAVIS-CI faz uma integração contínua com o código, rodando testes e trazendo os erros apresentados durante a execução, assim para cada pequena atualização que você fizer e der o push pra o projeto no github, ele estará rodando testes e lhe enviando e-mail notificando se encontrar algum problema.
Ele dá suporte a várias linguagens, inclusive as principais do mercado, PHP, Python, C#, JavaScript(com Node.js)
## Requisitos:
- Conta no [GitHub](https://github.com/) 
- Integrar conta com o [Travis-ci](https://travis-ci.org/)

## Utilização
A utilização é feita de forma simples, você precisa ter na raiz do seu projeto um arquivo chamado .travis.yml, dentro dele você colocará algumas informações, como a linguagem, a versão dela, e também pode colocar alguns scripts para ser rodado no servidor antes ou durante a execução.

Nesse repositório tem um .travis.yml simples apenas para demonstração.

Aqui você encontra a documentação completa: https://docs.travis-ci.com/

## Conceitos
Como travis-ci é uma plataforma de integração contínua, ele dará suporte ao processo de desenvolvimento, construindo e testando automaticamente alterações de código, fornecendo um feedback imediato sobre a execução.
Tendo como objetivo desenvolver softwares mais saudáveis, desenvolvendo e testando incrementos menores.
Ele também pode ser utilizado para fazer automatização da implementação do código direto no seu servidor, ou seja, após ele rodar seus testes, fará a implementação no seu servidor caso os testes ocorram tudo bem.
##  O que acontece por trás?
Quando você compila/envia para o github o travis-ci clona o repositório para dentro de um ambiente virtual e executa uma série de tarefas para criar e teste seu código, caso uma delas falhe a compilação será considerada interrompida. Se nenhuma tarefa falhar a compilação é considerada aprovada.
