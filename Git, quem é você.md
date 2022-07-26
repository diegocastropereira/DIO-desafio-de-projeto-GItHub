# Git, quem é você?

​	Para começar git, é uma ferramenta que no mundo de programadores é muito essencial. Simplificando, com o nosso amigo git, nós guardamos o nosso código, o que faz com que ele fique muito seguro (caso seu precioso computador seja roubado no meio da noite), além de que se você for sociável, seus amigos podem melhorar o seu código (não é legal)?

​	Como nem tudo é "mamão com açúcar" você tem que passar pelos testes muito complicados para usufruir dessa ferramenta criada por Linus Torvalds (o mesmo cara que criou o Linux!), umas das características que é bom saber: o "git bash", que é o local (na máquina) onde pode-se realizar algumas operações, não tem interface e sua utilização são com comandos muitos loucos (explicação adiante).

​	Introdução feita, agora o passo-a-passo para chegar na *Vale do Silício* (PIADA) :

1. Vá até o site do git: <https://git-scm.com/downloads>

2. Baixe de acordo com seu sistema operacional.

3. Abra o git bash.

4. Configure sua conta. (Dica se você já tem uma conta no **Git Hub**, use esses dados.)

   1. Criando sua conta...

   2. Comando para seu nome de usuário

      ```bash
      $ git config --global user.name "nomeDoUsuário"
      ```

   3. Coloque o mesmo usuário do Git Hub.

   4. Agora seu email: (o mesmo email do Git Hub)

      ```bash
      $ git config --global user.email "email@gmail.com"
      ```

   5.  O sistema vai te pedir uma autenticação, preencha os campos e _voilá_ conta criada com sucesso. Só precisa ser criada uma única vez.** : ) **

​	Ufa! Primeira tarefa concluída, para fazer seus uploads de código, a história é outra.

1. Navegue até a pasta (nos arquivos no computador é claro), e abra o git bash.
2. Use esse comando único sempre que você começar um novo repositório.

```bash
$ git init
```

3. Veja os arquivos (se o que vai para o repositório está ok).

   ```bash
   $ git status
   ```

 4. Adicione os arquivos (agora vai).

    ```bash
    $ git add .
    ```

 5. Nomeie seu *commit*: (é importante pois mantém o controle).

    ```bash
    $ git commit -m "nomeDoCommit"
    ```

    

É claro que tem muitas funções e outras coisas, porém vamos com calma esse é o meu primeiro repositório, e decidir explicar isso por que acho útil, é claro  que vou melhorar e transformar essa informação em algo digerível, enquanto isso não acontece tenha paciência! Obrigado 

-Diego Castro