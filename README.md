# aula_git_poo_rc

# GIT para quem é ADORÁVEL

- Criar um nova pasta: `mkdir nome-da-pasta`
- Entrar na pasta criada: `cd nome-da-pasta`
- Crio um repositório vazio: `git init`
- Abrir o vscode na pasta criada: `code .`
- Saber o estado do repositório: `git status`
- Criar um arquivo `code nome-do-arquivo.extensão`
- Adicione conteúdo ao arquivo e salve
- Adicionar o arquivo ao stage: `git add nome-do-arquivo.extensão`
- Fazer um commit: `git commit -m "Mensagem do commit"`
- Se o commit der erro, ele pode pedir pra identificar o usuário:
  - `git config --global user.name "Seu Nome"`
  - `git config --global user.email "email"`
- Fazer uma mudança e voltar para versão do commit
  - `git restore nome-do-arquivo.extensão`
  - Clicando no botão `Discard Changes` no vscode
- Fazer uma alteração e salvar via vscode
- Ver histórico de commits: `git log`

## Trabalhando remotamente

- Gosto de trabalho remoto ganhando em dólar, em real ou em euros.
- Criar um repositório no github, inicilando ele com um readme.md
- Clicar em criar codespace
- No codespace, alterar algo, e fazer o add, commit, push
- Verificar mudanças no github
- Alterar algo no repositório via interface web do github
- Puxar as modificações para o codespace utilizando `git pull`
