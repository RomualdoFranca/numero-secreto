# adicionando todos arquivos 
# git add .
Atentar ao espaço entre o add e o ponto

# remover um repositório remoto
Caso você não precise mais de um repositório remoto específico, pode removê-lo com o comando git remote remove apelido. Substitua 'apelido' pelo nome do repositório remoto que deseja remover. Aqui está um exemplo:

# git remote remove origin

# alterar a URL de um repositório remoto
Use o comando git remote set-url apelido nova_url para realizar essa atualização. Substitua 'apelido' pelo nome do repositório remoto e 'nova_url' pela nova URL que você deseja associar a ele. Aqui está um exemplo:

# git remote set-url origin https://github.com/seu-usuario/seu-repositorio.git

# Desafio

1. Crie uma conta no GitHub
2. Crie um repositório para um projeto pessoal.
3. Faça a instalação do Git
4. Crie um repositório localmente para o seu projeto pessoal
5. Adicione alguns arquivos no seu repositório local
6. Faça o commit das alterações
7. Configure a identidade do autor do commit.
8. Crie a branch Main
9. Realize a conexão do seu repositório local com o remoto
10. Envie as alterações no repositório local para o remoto
11. Utilize o comando git status

# reverter um commit
git revert 'id do commit'
# Ex: git revert b67ece9fceef7c32ace3c5cad45e548fdcd88b0d
É como se fosse um ctrl-Z

# resetando um commit
Isso é feito enquanto a alteração está no repositório local. Também é necessário saber o ID do commit
Apaga um commit do histórico
Ex: git reset --hard 'id do commit'
# OBS: o ID deve ser do commit anterior ao commit que se quer resetar
