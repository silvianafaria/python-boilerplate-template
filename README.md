Python boolerplate :ramen:
===

## Sobre este repositório :open_book:

Repositório criado como código fonte básico para iniciar trabalhos em Python :snake:.

Um breve :movie_camera: [tutorial no YouTube](https://youtu.be/Ul-BMpLrWMU) foi criado para facilitar o entendimento e a construção do repositório.

## Apoie este trabalho :money_with_wings: :money_with_wings: :money_with_wings:

Se você gostou deste conteúdo e deseja auxiliar na criação de mais material como esse, pague-nos um café!!! :coffee:

[Pix: pagueumcafepgabriel@gmail.com](https://iti.itau/transacoes?t=link&h=f5fa1d7a-d3cd-4502-b62f-3eac451528a6)

Algo não funcionou, ficou com alguma dúvida ou gostaria de aprofundar algum ponto específico não detalhando no vídeo ou no código? Envie um e-mail para pagueumcafepgabriel@gmail.com para agendarmos uma sessão de tutoria online.

## Utilizar boolerplate :open_book:

- Clonando o projeto:

```Python
$ git clone https://github.com/gabrielbdornas/python-boolerplate <nome-do-seu-projeto>
$ rm -rf .git
$ git init
$ git add .
$ git commit -m "First Commit - Using python boolerplate"
$ python3.9 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
# inclua no arquivo requirements.txt todas as bibliotecas necessárias p seu projeto
```

## Criar seu próprio boolerplate (o céu é o limite) :open_book:

- Criação pasta do projeto:

```Python
$ mkdir <project-name>
```

- Iníciando ferramenta de controle de versão git:

```Python
$ cd <project-name>
$ git init
```

- Configurando .gitignore file:

```Python
$ touch .gitignore
# Copiar e colar conteúdo: https://github.com/github/gitignore/blob/master/Python.gitignore
# Arquivo raw: https://raw.githubusercontent.com/github/gitignore/master/Python.gitignore

$ git status
# Deverá apresentar:

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
  .gitignore

nothing added to commit but untracked files present (use "git add" to track)
```

- Criando ambiente (Python versão 3.9):

```Python
$ python3.9 -m venv venv
# git status não deverá apresentar pasta venv criada

$ echo "ipdb==0.13.9" > requirements.txt
# local aonde pacotes necessários serão armazenados
# cria arquivo requirements.txt já com pacote para debug

$ source venv/bin/activate
# desativar o ambiente basta digitar o comando "deactivate"

$ pip install -r requirements.txt
# Incluir pacote no arquivo requirements.txt antes de rodar o comando acima

$ git status
# Deverá apresentar:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
  .gitignore
  requirements.txt

nothing added to commit but untracked files present (use "git add" to track)
```

- Criar arquivo README.md:

```Python
$ touch README.md
```

- Commitar boilerplate:

```Python
$ git add .
$ git commit -m "First Commit - Seting-up project"
```

- Renomeando branch do projeto (para subir projeto no github):

```Python
$ git branch -m master main
```

- Criação repo github.
- Subindo projeto github:

```Python
$ git remote add origin git@github.com:<github-account>/<project-name>.git
$ git push -u origin main
```

## Encontrou algo errado no código ou quer melhorá-lo

[Fork](https://github.com/login?return_to=%2Fgabrielbdornas%2Fpython-base-project) o repositório e abra um Pull Request!!! Prometo não demorar a responder.

Adoro este tipo de contribuição pois auxiliará no crescimento do código de maneira exponencial!
