Anotações comandos base cmd:

incio: windows -> cmd

__________________________________________________________________________

acessando uma pasta:

cd (nome da pasta)

__________________________________________________________________________

saindo de uma pasta:

cd..

__________________________________________________________________________

vendo oq existe dentro de uma pasta:

dir

ls

__________________________________________________________________________

vendo pastas ocultas:

ls -a

__________________________________________________________________________

criando uma pasta:

mkdir (nome da pasta)

__________________________________________________________________________

deletando uma pasta:

rmdir (nome da pasta)

__________________________________________________________________________

deletando todos os prints do cmd:

cls

__________________________________________________________________________

printando uma msg:

echo (msg)

__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________

criando um usuario no GIT:

git config --global user.email "(email)"
EX: git config --global user.email "mguellntr@gmail.com"

git config --global user.name "(nome)"
EX: git config --global user.name "(nome)"

__________________________________________________________________________

iniciando um repositorio no git:

git init

(antes de usar o init, tenha certeza que voce esta na pasta que voce quer estar usando os comandos de locomoção do cmd)

__________________________________________________________________________

adicionando um novo git a um repositorio existente:

git add "(nome do item que voce quer adicionar)"
EX: git add "bolo-de-cenoura.txt"

PS: git add * pega todos os arquivos dentro da pasta

__________________________________________________________________________

criando um commit:

git commit -m "(msg que será gravada no commit)"

boas praticas: coloque msgs que ditem oq foi adicionado / alterado.

__________________________________________________________________________

vendo o código sha1:

openssal sha1 "(nome do arquivo)"

PS: esteja dentro da pasta do arquivo para usar esse comando.

__________________________________________________________________________

vendo os commits que foram feitos:

git log

__________________________________________________________________________

git status: diz o status de todos os itens dentro daquela pasta

__________________________________________________________________________

voltando um estágio no processo do commit:

"ah, esqueci de uma coisa no meu arquivo"

git restore --stage "(nome do arquivo)"

PS: isso pra antes do commit, pra depois do commit se usa: "(git revert numero_bash)"
__________________________________________________________________________

renomeando uma arquivo:

git mv (nome do arquivo) (novo nome do arquivo)

PS: tenha certeza se esta dentro da pasta do arquivo

__________________________________________________________________________
__________________________________________________________________________

Removendo um usuario:

git config --list -> mostra todos os usuarios e emails setados
git config --global --unset user.email "(email setado)"
git config --global --unset user.name "(nome setado)"

__________________________________________________________________________


