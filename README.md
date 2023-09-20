<h1 align = center> <ins> Anotações Comandos Basicos cmd: </ins> </h1>

<h2 align = center> incio: windows -> cmd </h2>

<h3> <li> acessando uma pasta: </li> </h3>

    cd (nome da pasta)

<hr></hr>

<h3> saindo de uma pasta: </h3>

    cd..

<hr></hr>

<h3> <li> vendo oq existe dentro de uma pasta: </li> </h3>

    dir

    ls

<hr></hr>

<h3> <li> vendo pastas ocultas: </li> </h3>

    ls -a

<hr></hr>

<h3> <li> deletando todos os prints do cmd: </li> </h3>

    cls

__________________________________________________________________________
__________________________________________________________________________

<h1 align = center> <ins> Anotações Comandos Basicos GIT: </ins> </h1>

<h3> <li> criando um usuario no GIT: </li> </h3>

    git config --global user.email "(email)"
    EX: git config --global user.email "mguellntr@gmail.com"

    git config --global user.name "(nome)"
    EX: git config --global user.name "(nome)"

<hr></hr>

<h3> <li> iniciando um repositorio no git: </li> </h3>

    git init

<i> (antes de usar o init, tenha certeza que voce esta na pasta que voce quer estar usando os comandos de locomoção do cmd) </i>

<hr></hr>

<h3> <li> adicionando um novo git a um repositorio existente: </li> </h3>

    git add "(nome do item que voce quer adicionar)"
    EX: git add "bolo-de-cenoura.txt"

<i> PS: git add * pega todos os arquivos dentro da pasta </i>

<hr></hr>

<h3> <li> criando um commit: </li> </h3>

    git commit -m "(msg que será gravada no commit)"

<i> boas praticas: coloque msgs que ditem oq foi adicionado / alterado. </i>

<hr></hr>

<h3> <li> vendo os commits que foram feitos: </li> </h3>

    git log

<hr></hr>

<h3> <li> git status: diz o status de todos os itens dentro daquela pasta </li> </h3>

<hr></hr>

<h3> <li> voltando um estágio no processo do commit: </li> </h3>

    "ah, esqueci de uma coisa no meu arquivo"

    git restore --stage "(nome do arquivo)"

<i> PS: isso pra antes do commit, pra depois do commit se usa: "(git revert numero_bash)" </i>

<hr></hr>

<h3> <li> Removendo um usuario: </li> </h3>

    git config --list -> mostra todos os usuarios e emails setados

    git config --global --unset user.email "(email setado)"

    git config --global --unset user.name "(nome setado)"

__________________________________________________________________________
__________________________________________________________________________

<h1 align = center> <ins> Anotações Comandos Basicos, Interligando GIT com GIThub: </ins></h1>

<h3> <li> interligando o git com o github: </li> </h3>

    git remote add origin (colar o link do http sem aspas nem parenteses)

    git remote -v -> ver se o git está conectado com o github

    git push origin master -> enviar conteudo da pasta para o git

<i> PS: tenha certeza q está nas pasta certa. </i>

<hr></hr>

<h3> <li> clonando um arquivo do github para o git local: </li> </h3>

    git clone (link do github(link do botão CODE))

<hr></hr>

<h3> <li> add um novo branch ao reposirotorio: </li>  </h3>

<i> primeiro tenha certeza de ter criado um branch no repositorio alvo </i>

    git clone "(link do repositorio)" -> clona tudo do repositorio para o pc
<i> (antes de usar o init, tenha certeza que voce esta na pasta que voce quer estar usando os comandos de locomoção do cmd) </i>
<i> enter no pasta que foi clonada </i>

    git pull -> para atualizar o repositorio

    git branch -a -> ver todos os branch criados
    
<i> (veja se o seu já criado no meio de tudo) </i>

    git checkout (nome do seu branch)

    git status -> para ver se todos o seus arquivos do seu branch estão atualizados

    git add -> em caso de estar faltando algo (se tiver algo vermelho)

<i> para finalizar: </i>

    git commit -m "(msg do commit)"

    git push
