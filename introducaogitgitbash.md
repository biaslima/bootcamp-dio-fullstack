Introdução ao Git e GitBash 

# Comando Principais no Git Bash

- git init → cria um repositório no diretório
    - Basicamente inicia-se um repositório vazio
- git add [arquivo] → manda arquivo para a área de staging
    - Esse comando deixa o arquivo preparado para ir para a area de commit
    - git add . → envia para staging todos os arquivos disponíveis
- git status → mostra as mudanças que estão em staging, ainda não foram commitadas
- git commit -m “[nome/mensagem do commit]” → envio o arquivo atualizado para o commit
- git branch -M “[novo nome da branch]” → renomear branch atual
- git remote add origin [link do repositório no github] → faz a ligação do repositório do git no pc com o repositório no github
- git push -u origin main → empurra os commits do repositório local para o gith
- git remote rm → remove url remota
- git checkout -b “[nome da branch]” → cria uma nova branch
- git checkout [nome da branch] → vai para a branch desejada
- git merge [nome da branch] → unir a branch cujo o nome você escreveu com a branch atual que você está
- git clone [url do repositório que deseja clonar] → puxar repositório de alguém para a máquina
- git pull → puxa commit do repositório clonado

# Comandos Básicos para um Bom Desempenho do Terminal

- dir → lista as pastas
    - ls -a → mostra aruivos ocultos
- cd → navega para um local específico no sistema e lista as pastas
    - Retornar ao primeiro local: cd ..
- cls ou ctrl + l → limpar terminais
- mkdir → criar pasta
- “echo” + palavra → impressão
- “echo” + palavra + > + palavra.txt  → cria arquvio txt com a palavra
- del → deletar arquivos da pasta
- rmdir → apagar pasta vazia
- rmdir workspace /S /Q → apagar pasta não vazia

# Ciclo de Vida de um Arquivo no Git

- Git Init → criação de repositório em um diretório

### Tracked e Untracked

- Tracked → arquivos os quais o git sem ciência
    - Unmodified → arquivo não modificado
    - Modified → arquivo modificado
    - Staged → arquivo se preparando para fazer parte de um commit
- Untracked → git não tem ciência do arquivo

## Conceitos

- Branch → ramificação do seu código/projeto