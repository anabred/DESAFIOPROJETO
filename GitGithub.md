# GIT/GITHUB :robot:

GIT não tem interface gráfica, ele é por linhas de código.
O que vamos aprender?
Mudas de pastas
Listas as pastas
Criar pastas/arquivos
Deletar pastas/arquivos

 

Abrir Git

Comando Listar: dir (Windows)
Vai listas todas as pastas.

Comando navegar pastas: cd Windows – entra dentro da pasta Windows
cd.. – volta a pasta anterior
cls – limpa o terminal ou cntrl + L
mkdir – criar diretório. Ex. mkdir workspace (cria a pasta workspace). CRIAR ESSA PASTA NO MEU PC

cd workspace – entra na pasta workspace
echo hello – imprime “hello” na tela
echo hello > hello.txt – vai criar o arquivo hello.txt

del workspace – apaga os arquivos da pasta workspace (só deleta arquivo)

rmdir wokspace /S /Q – deleta a pasta wokspace


OBETOS INTERNOS DO GIT
BLOBS
	 

TRESS
	Armazenam blobs

COMMITS


ls -a     -mostra arquivos ocultos
git init
	comando para inicializar repositório dentro daquele diretório (pasta)
	Quando criamos o arquivo Strogonoff.md no Typora ele estava Untracked. Após o comando git add *....
Tracked
	Após o comando git add * ele foi pro tracked.

git config --list - para listar configurações
git config --global --unset user.email - vai pedir novamente no próximo commit.
git config --global user.email "XXXXX"

$ git remote add origin https://github.com/anabred/livro-receitas
git remote -v

git push origin master
git pull origin master   - puxa o conteúdo quando tem conflito

git clone (URL Q PEGA ANO GITHUB)
git status

para enviar a pasta depois de clonada e alterada

git add *

git commit -m "MENSAGEM"

PUSH PARA ENVIAR GITFHUB
git push origin main