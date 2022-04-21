# Comandos básicos no Git

## Para acessar o Git Bash em determinada pasta, basta estar na pasta escolhida e clicar com botão direito do mouse e clicar em Git Bash Here;

**No terminal do Git Bash**

- Clonar repositório do GitHub para máquina local:
    git clone "link do repositório"

- Verificar se há alguma alteração:
    git status

- Adicionar todas as alterações para o controle de versão LOCAL:
    git add . ou git add -A

- Commitar as alterações na máquina local:
    git commit -m "comentário entre aspas para descrever o commit"

- Realizar push para repositório na nuvem:
    git push origin main  (main é a branch principal, atentar-se)
