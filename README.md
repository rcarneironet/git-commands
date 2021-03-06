# git-commands
Commands used often while using GIT

# analisar versão
git version

# iniciar um repositório local
git init

# analisar status do GIT
git status

# adicionar
git add . (extensão ou tudo)
git add *.c (extensão ou tudo)

# remover alteração cacheada
git rm --cached <arquivo> (extensão ou tudo)

# limpar alterações de forma forçada
git clean -f

# ver conteudo alterado
git diff

# adicionar repositório remoto de origem
git remote add origin <URL> (precisa ser um repositório .git)

# visualizar remotos
git remote show origin

# alterar remotos
git remote rename <valor_antigo> <novo_valor> <remote>

# remover remotos
git remote remove <remote>

# clonar repositório
git clone <URL> (precisa ser um repositório .git

#  exibir branches - local e remoto
git branch -a 

# exibir branches - remoto apenas
git branch -r (apenas remoto)

# criar um branch
git checkout -b <nome_do_branch>

# remover um branch local
git branch -d <branch>

# remover um branch remoto
git push --delete <branch>

# fetch
git fetch origin <branch>

# pull
git pull origin <branch>

# commit
git commit -m "mensagem_commit"

# push
git push origin <branch>

# merge
git checkout <branch_principal>
git merge <branch_origem>

# ignorar alteracoes
git checkout -- <arquivo>

# visualizar tags
git tag

# visualizar tags (listagem)
git tag -l

# visualizar tags (por id)
git show <tag>

# criar tag
git tag -a v1.4 -m "my version 1.4"

# log de commits
git log
