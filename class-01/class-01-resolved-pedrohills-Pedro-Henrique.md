# Node.js - Aula 01 - Exercício

1. Explique como um processo síncrono e assíncrono roda no Node.js, dê um exemplo para cada.
2. Como o V8 executa JavaScript? Demonstre 1 exemplo com código ou imagem.
3. Qual a diferença entre um sistema single para um multi-thread?
4. Como a Thread Pool tem um tamanho padrão de 4, o que acontece se você enviar 5 requisições ao banco?
5. Como você venderia o peixe do Node.js na sua empresa para tentar convencer seu chefe da sua adoção?
6. Qual a versão do seu `node`?
7. Qual a versão do seu `npm`?

## Estrutura

```md
# Node.js - Aula 01 - Exercício
**user:** pedrohills(Link para seu Github)
**autor:** Pedro Henrique
**date:** 1454517126551


## Explique como um processo síncrono e assíncrono roda no Node.js, dê um exemplo para cada.
R- Um processo síncrono no NodeJS segue como um garçom de um restaurante que está atendendo um cliente e ele só atende um segundo cliente caso o primeiro já tenha sido totalmente atendido. Em um processo assíncrono no NodeJS, usando o mesmo exemplo do restaurante, o garçom atende os clientes e seus pedidos são entregues assim que eles estão prontos.

## Como o V8 executa JavaScript? Demonstre 1 exemplo com código ou imagem.
O V8 na verdade não executa código JavaScript puro, ele primeiramente compila, em tempo de execução, o código que foi escrito em JavaScript em Código de Máquina. Para isso, ele utiliza um compilador JIT (Just-In-Time).

## Qual a diferença entre um sistema single para um multi-thread?
Uma thread permite, por exemplo, que o usuário de um programa utilize uma funcionalidade do ambiente enquanto outras linhas de execução realizam outros cálculos e operações.

Em hardwares equipados com uma única CPU, cada thread é processada de forma aparentemente simultânea, pois a mudança entre uma thread e outra é feita de forma tão rápida que para o utilizador, isso está acontecendo paralelamente. Em hardwares com múltiplos CPUs ou multi-cores, as threads são realizadas realmente de forma simultânea.

Os sistemas que suportam uma única thread (em real execução) são chamados de monothread enquanto que os sistemas que suportam múltiplas threads são chamados de multithread.

Fonte: https://pt.wikipedia.org/wiki/Thread_(ci%C3%AAncia_da_computa%C3%A7%C3%A3o)

## Como a Thread Pool tem um tamanho padrão de 4, o que acontece se você enviar 5 requisições ao banco?
Elas serão incluías na Idle-Thread e ficarão aguardando a Thread Pool liberar espaço para poderem irem para lá.

## Como você venderia o peixe do Node.js na sua empresa para tentar convencer seu chefe da sua adoção?
Equipe, ao utilizarmos NodeJS em nossos sistemas estaremos resultando em um menor gasto com equipamentos quando formos trabalhar sua escalabilidade.

Trabalharemos com tecnologia de ponta que atendeu grandes corporações que recebem milhares de requisições por minuto. Tenho a certeza de estarmos preparados para o sucesso e o NodeJS será a ferramenta que nos levará até ele mais rápido.

## Qual a versão do seu `node`?
v5.2.0
## Qual a versão do seu `npm`?
3.3.12
```


## Envio

[Veja na nossa Wiki](https://github.com/Webschool-io/be-mean-instagram/wiki/Exerc%C3%ADcios)

1. Crie o repositório específico do módulo. Ex.: be-mean-instagram-mongodb
2. Crie a solução do exercício localmente nesse repositório, usando sempre o padrão `class-X-resolved-githubuser-Nome-Completo-Com-Hifens-Nos-Espaços.md`
3. Dê um `fork` no repositório oficial [https://github.com/Webschool-io/be-mean-instagram-nodejs-exercises](https://github.com/Webschool-io/be-mean-instagram-nodejs-exercises)
4. Vá até a pasta do módulo desejado e **COLE** seu arquivo na pasta `exercises`
5. Execute um `git add NOME_DO_SEU_ARQUIVO.md` depois o `git commit -m 'SEU NOME - Node.js - Exercicio X resolvido'`
5. Crie um **Pull Request** enviando **APENAS** o seu arquivo sem modificar mais nada.
6. Na mensagem do commit/pull request favor seguir o padrão: Nome Completo - Node.js - Exercicio X resolvido
7. Levante as mão para o céu e agradeça se acaso tiver ... #brinks