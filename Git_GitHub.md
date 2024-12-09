# Git e GitHub

## O que é Git?

O **Git** é um sistema de controle de versão de arquivos onde registra as alterações feitas em um repositório ou software podendo regredir para versões anteriores caso necessário de forma simples e rápido. Também permite que varias pessoas possam contribuir de forma simultânea o repositório, adicionando, removendo e editando os arquivos.


## Estados do **Git**

* *Modified* (Modificado) 

* *Index / staged* (Preparado)

* *Committed* (Consolidado)

* *Untracked* (Não rastreado)


## Configurando o **Git** com *.gitconfig*

Para enviar as modificações e começar a trabalhar com o **Git**, é importante configurá-lo através de um arquivo na raiz do seu usuário chamado de *.gitconfig* e para configurar esse arquivo, você pode usar um editor de texto ou os comandos:

* `git config  —global user.name “Nome da sua conta”`: Configura o nome de usuário.

* `git config —global user.email “Nome do email”`: Configura o email do usuário.

* `git config —list`: Lista as configurações.


## Comandos do **Git**

* `git init`: Inicia o **Git** e cria um repositório.

* `git clone`: Baixa o repositório online para trabalhar localmente.

* `git fetch`: Atualiza o repositório para ver alterações, mas não aplica elas.

* `git status`: Exibe o estado do repositório.

* `git pull`: Baixa as mudanças do repositório.

* `git add`: Adiciona as modificações do repositório desde um arquivo novo, arquivo excluído, arquivo modificado, novo diretório e remover diretório. Ex: git add arquivo.txt (**OBS**: Para adicionar todas as modificações de uma vez, digite `git add .`).

* `git rm`: Remove um arquivo do **Git**. Ex: `git rm arquivo.txt`. (**OBS:** Pode também deletar do disco.).

* `git rm –m`: Remove um diretório do **Git**. (**OBS:** Pode também deletar do disco.).

* `git commit -m`: Escreve uma mensagem e prepara a modificação para ser enviada ao repositório.

* `git push`: Envia os _commits_ para o repositório.

* `git _branch_`: Lista as _branch_ locais.

* `git push -u origin "Nome da branch"` ou `git push —set-upstream origin “Nome da branch”`: Define o repositório remoto e link com a _branch_ local. (**OBS**: Ele cria automaticamente a _branch_ remota caso não tenha criado.).

* `git push -d origin "Nome da Branch"`: Deleta uma _branch_ remota.

* `git branch “Nome da branch”`: Cria uma nova _branch_ local.

* `git branch –d “Nome da branch”`: Exclui a _branch_ local.

* `git branch -M "Nome da branch" "Novo nome da branch"`: Renomeia uma branch local.

* `git checkout “Nome da branch”`: Muda de _branch_ local.

* `git remote`: Exibe as _branch_ remota.

* `git remote remove`: Exclui _branch_ remota.

* `git merge “Nome da branch”`: Faz a mescla de uma _branch_ na atual.

* `git log`: Mostra o histórico dos _commits_.

* `git commit —amend`: Modifica o ultimo _commit_. (**OBS:** Ira abrir um editor de texto para modificar o _commit_.).

* `git commit —amend –m “Nova mensagem”`: Modifica somente a mensagem do ultimo _commit_.

* `git revert “Hash do commit para voltar”`: Cria um novo _commit_ a partir de um _commit_ antigo.

* `git tag “Nome da tag”`: Cria uma _tag_ simples.

* `git tag –a “Nome da tag” –m`: Cria uma _tag_ com mensagem.

* `git push —tags`: Envia as _tags_ para o remoto.

* `git tag -d`: Exclui uma _tag_.

* `git help`: Exibe a documentação do git ou de um comando especifico.


## Adicionando Coautores em um *commit*

Para poder adicionar um coautor a um *commit*, você deve saber o email e nome de usuário do **Git** dele; se ele utiliza email privado do **GitHub,** use o email *no-reply*. Apos isso coletar as informações, siga esses passos:

1. Escreva a mensagem do *commit* e depois em vez de inserir aspas para encerrar, adicione duas linhas vazias. Ex:

        git commit -m "Mensagem.
        >
        >

2. Na proxima linha adicione `Co-authored-by: name <name@example.com>` e substitua com as informações do coautor. Se tiver mais coautores, de a cada um a linha própria sem deixar linhas vazias entre um e outro. Apos digitar a quantidade que quiser de coautores, feche as aspas duplas. Ex: 

        git commit -m "Mensagem.
        >
        >
        Co-authored-by: coautor1 <coautor1@example.com>
        Co-authored-by: coautor2 <coautor@example.com>"


## O que é **GitHub**?

O **GitHub** é uma plataforma de hospedagem de código-fonte e arquivos usando o **Git**, permitindo que usuários da plataforma possam criar e contribuir com projetos privados ou *open source* de qualquer lugar do mundo. O **GitHub** esta disponível nas versões Web (Mais completa e fácil), Desktop (Fácil e intuitivo de usar) e CLI (Terminal).
