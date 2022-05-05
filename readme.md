Sobre o readme <br>
Instrução sobre o funcionamento do condigo, uma introdução ao projeto. 

# Tutorial GIT 
Projeto para aprender a utilizar o git :)

## Seja bem vindo! <3

### Códigos principais 
    git init
inicializa o git no diretório 

    git add .
adciona o diretório no gatilho para o commit, o **.** representa que toda a pasta está adicionada, pode ser substituida pelo nome do arquivo. Envia para a area de stage (espera)

    git status 
Visiualiza informações sobre o projeto 

    git commit -m "mensagem de commit"

    git branch -M "nomedanovabranchmaster"
Altera o nome da branch master 

    git remote add origin https://github.com/lulves/Curso-alura-GIT.git
adiciona o projeto que está sendo controlado pelo git no repositorio do github. remote = conexão remota. add = adicionar. origin é o nome padrão (que pode ser alterado) do repositorio no github 

    git push -u origin main 
tudo que está no repositorio local passa pro remoto. push é um empurrão é literalmente empurrar os aquivos que estão salvos localmente para o repositorio remoto. main é o nome da branch que estou enviando. 

    git marge nome-da-branch
une a branch nome-da-branch na branch principal 
   
    git checkout -b "nova-funcionalidade"
cria um nova branch 
nova-funcionalidade

    git clone caminho 

    git pull
puxa as atualizações feitas por outros no git para o meu diretório local
