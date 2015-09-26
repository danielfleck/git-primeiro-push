PRIMEIRO PUSH DO CURSO DE GIT
=============================

Passos para criar o repositório e executar o primeiro push
----------------------------------------------------------

1. Criar o repositório no github;

2. Clonar o repositório para o computador;

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

Obs.: Também é possível criar uma tag passando como parâmetro o commit que tag deve fazer referência
    ```shell
    git tag 0.1.0 master
    ```
