# Latex

- Este repositório está hospedado na seguinte URL: https://bergolho1337.github.io/Latex/

- Para conseguir isto estou utilizando o GitHub-Pages 

- Passos para configurar um repositório do GitHub como GitHub-Pages:
    1) Criar um repositório no GitHub;
    2) Criar uma nova branch com o nome 'gh-pages';
    3) Definir esta nova branch como a padrão;
    4) Deletar a branch 'master'
    5) A URL fica acessível como:  https://<username>.github.io/<repository_name>/

- Assim é possível adicionar um arquivo 'index.html' e configurar uma página Web (CSS + Javascript) e que tenha links para os arquivos do repositório. :-)

- ATENÇÃO: Lembre-se que a branch 'master' não existe, logo o comando padrão para o push fica:

```sh
$ git add *
$ git commit -m "Message"
$ git push origin gh-pages
```
