# Markdown-and-Git

Caso Não Haja No Codigo README.MD o Comando Necessario, Busque no Documents Do GitLab

[Documents GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
<br>

Aprimorando Conhecimento em Markdown e Listando Comandos GIT Importantes!.

# Principais Comandos do Git

## Configuração Inicial

- `git config --global user.name "seu nome"`: Define o nome do usuário.
- `git config --global user.email "seu email"`: Define o email do usuário.

## Criando um Repositório

- `git init`: Inicializa um novo repositório Git na pasta atual.
- `git clone url_do_repositório`: Clona um repositório remoto.

## Trabalhando com Arquivos e Commits

- `git status`: Mostra o estado atual do repositório, incluindo quaisquer alterações não confirmadas.
- `git add nome_do_arquivo`: Adiciona um arquivo ao próximo commit.
- `git commit -m "mensagem do commit"`: Cria um novo commit com as alterações adicionadas.
- `git log`: Mostra o histórico de commits.

## Trabalhando com Branches

- `git branch`: Lista todas as branches do repositório.
- `git branch branch_name`: Cria uma nova branch.
- `git branch -d branch_name` : Deletar uma branch
- `git checkout branch_name`: Muda para a branch especificada.
- `git merge branch_name`: Mescla a branch especificada na branch atual.
- `git diff branch`

## Trabalhando com Repositórios Remotos
- `git remote`: Mostra qual repositorio estamos conectados no momento - se não tiver nenhum conectado, não apareça nada.
- `git remote add origin url_do_repositório`: Adiciona um repositório remoto.
- `git push origin branch_name`: Envia as alterações para o repositório remoto.
- `git pull origin branch_name`: Recebe as alterações do repositório remoto.
