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

`git status`

Verificar o status atual do repositório

`git add nomearquivo` ou `git add .`

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração`

Fazer commit das alteração (salvar no histórico).