id: git-exemplo1
summary: "Nesse codelab, você irá aprender a criar sua trabalho acadêmico com as normas da ABNT utilizando Markdown."
url: limarka-exemplo1
category: "Web"
environment: web
status: Draft
author: edusantana
feedback link: https://github.com/abntex/limarka/issues
formatting help: https://github.com/googlecodelabs/tools/tree/master/claat/parser/md


## Aprendendo a utilizar o git

Duration: 02:10

O git é um sistema de controle de versão de arquivos.

## Aonde aprender sobre o git

Duration: 01:10
Environment: Web, Kiosk


- [Livro Pro Git - Primeira versão (em português)](https://git-scm.com/book/pt-br/v1)
- [Livro Pro Git - Segunda versão (tradução para português em progresso)](https://git-scm.com/book/pt-br/v2)
- [Última versão do livro (em inglês)](https://git-scm.com/book/en)

## Introdução

Duration: 01:00
Environment: Web
Raiz: Algo mais


- O git é uma ferramenta de controle de versão.
- O git funciona utilizando repositórios de arquivos descentralizados (existem vários repositórios)
- O Github é uma empresa que vende hospedagens para repositórios on-line e oferece repositórios gratuítos para projetos de código aberto.

## Atividades

### 1. Criar um repositório para guardar arquivos para um projeto de uma disciplina

Nesta atividade você irá criar um repositório para hospedar os arquivos de um projeto

1. Escolham um projeto de disciplina (se não tiver um projeto, invente um).
2. Vá ao github e crie um repositório para o projeto escolhido. (Lembre-se de marcar que deseja criar um arquivo README)
3. Depois que o projeto for criado, edite o arquivo `README.md` e adicione um parágrafo explicando o projeto.

### 2. Clonando o repositório

Nesta atividade você irá clonar o repositório remoto para a máquina local.

Utilize o comando `git clone` no terminal para clonar o repositório.

AJUDA:

- [Capítulo do livro explicando como obter um repositório](https://git-scm.com/book/pt-br/v1/Git-Essencial-Obtendo-um-Reposit%C3%B3rio-Git)
- [Ajuda no github (em inglês)](https://help.github.com/articles/cloning-a-repository/)


## 3. Adicione arquivos e comite ao repositório local

Nessa atividade você irá adicionar arquivos aos repositório local criando um commit com os arquivos. Baixe ou crie alguns arquivos para serem adicionados. Pode ser, por exemplo, as intruções do projeto a ser realizado.


Exemplo para marcar arquivos para serem comitados:

        git add nome-do-arquivo1
        git add nome-do-arquivo2 nome-do-arquivo3
        git add *.pdf

Antes de comitar é importante verificar as alterações que estão marcadas para o commit:

        git status

Para realizar um commit precisando fornecer uma mensagem explicando a alteração que estamos enviando para o repositório, ex:

        git commit -m "Adicionando as instruções do projeto"

## 4. Perceba que as alterações ainda não foram enviadas para o repositório remoto

        git status

Acesso o repotisório remoto no github e verifique que o arquivo não foi adicionado.

## 5. Enviando os commits para o repositório remoto

        git push

## Criando páginas estáticas

Vamos utilizar o recurso de [Github Pages](https://pages.github.com/) para criar páginas da WEB estáticas.

## Outro teste

Mais texto aqui.
