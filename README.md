# Exemplos de operações básicos para git via CLI

## Comandos de uso geral da CLI

- Criar pasta: mkdir nomedapasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entrar na pasta: cd nomepasta

## Comandos principais do git

`git config --global user.name "Seu nome como quiser"` e `git config --global user.email "seuemail@provedor.com"`

Mudar usuário e e-mail de forma global

**Obs:** normalmente estes dados estão relacionados ao usuário/conta do site GitHub.

`git config user.name` e `git config user.email`

Verificar usuário/email

`git init` 

inicializar um repositório (executando dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`

Renomear branches.

Para alterar a branch de **master** para **main** (novo padrão), usaríamos: `git branch master main `

`git status`

Verificar o status atual do repositório

`git add nomearquivo` ou `git add .`

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração`

Fazer commit das alteração (salvar no histórico).

`git remote add origin endereço-do-repositório.git`

Adicionar/conectar o repositório remoto ao local 

`git clone endereço-do-repositório.git`

Copiando/baixando um repositório para a máquina remota:

`git push origin main`

Enviar as mudanças para o GitHub (PUSH).

`git pull origin main`

Pegar/Obter as mudanças do repositório online GitHub (PULL).