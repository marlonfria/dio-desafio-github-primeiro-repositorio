#Resumo da Aula

##Primeiros comando com Git

**Iniciar o Git**
git init

**Iniciar o versionamento**
git add

**Criar um commit**
git commit


** Como criar um repositório?**
mkdir nomedorepositório
cd nomedorepositorio
git init

**Listar arquivos ocultos**
ls -a

**Configurar usuário e email**
git config --global user.email email@email.com
git config --global user.name "Nome do usuário"


**Markdown - alguns comandos**
"# = cabeçalhos"
"** = negrito"
"- = lista não ordenada"

git add *
git commit -m ""


**Alguns comandos**
git add =  move do untracked para o staged

commit = move arquivos do staged para unmodified

mkdir = cria um novo diretório

mv = move arquivos

git status = detalhes das modificações nos diretórios

readme.md = capa do repositório


**Lista todas as configurações do git**
git config --list


**Remove a configuração do nickname do git**
git config --global --unset user.nickname

**linkar repositório local ao remoto**
git remote add origin "linkdorepositóriocriadonogithub"

**Remove arquivos de um repositório definitivamente** 
git rm nomedoarquivo.txt

**Leva os arquivos do repositório local para o remoto**
git push origin master
