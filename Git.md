# Cartilha Git

Esse documento descreve os principais comandos do Git e sua integração com Github

## Autenticação

Para salvar as credenciais de acesso ao Github, de forma que não sejam exigidas a cada comando push/pull, basta seguir o seguinte procedimento:
Execute o comando `git config --global credential.helper store` e então `git pull`, serão exigidas suas credenciais. Após validadas, suas credenciais serão salvas em `~/.git-credentials`, a partir de então o git passa a buscar suas credenciais desse arquivo, não sendo necessário digitar novamente após cada comando.

## Comandos gerais

* `git init` inicia um projeto
* `git add .` adiciona ou atualiza mudanças a serem incluídas na timeline
* `git commit -m "commit message"` adiciona um ponto na timeline
* `git log` lista os pontos/commits na timeline
* `git status`lista o estado das alterações no projeto
* `git show` exibe determinado ponto na timeline
* `git branch` gerencia as timelines
* `checkout` seleciona uma determinada timeline
* `git merge` une duas timelines
* `git push` envia alterações locais (commits) para o repositório remoto
* `git clone` clona um projeto/repositório
* `git pull` busca atualizações no repositório remoto

**[Retornar ao índice](README.md)**