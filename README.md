PRIMEIRO PUSH DO CURSO DE GIT
=============================

Passos para criar o reposit�rio e executar o primeiro push
----------------------------------------------------------

1. Criar o reposit�rio no github;

2. Clonar o reposit�rio para o computador;

    ```shell
    git clone git@github.com:danielfleck/git-primeiro-push.git
    ```

3. Editar o arquivo README.md

4. Adicionar o arquivo
    ```shell
    git add README.md
    ```

5. Realizar o commit
    ```shell
    git commit -m "Cria o arquivo README"
    ```

6. Executar o push
    ```shell
    git push origin master
    ```

Passos para criar uma tag
-------------------------

1. Fazer checkout no commit referente a tag que deve ser criada
    ```shell
    git checkout master
    ```

2. Criar a tag
    ```shell
    git tag 0.1.0
    ````

Obs.: Tamb�m � poss�vel criar uma tag passando como par�metro o commit que tag deve fazer refer�ncia
    ```shell
    git tag 0.1.0 master
    ```
