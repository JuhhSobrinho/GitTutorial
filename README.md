# GitTutorial
## Inicializando Git e dando primeiro commit
1. `git init` para **inicializar** o repositorio<br>
1. `git add .` para separar os arquivos para o **commit**<br>
1. `git commit -m "primeiro commit"` para dar o real commit com sua mensagem e preparação para o **push**<br>
1. `git branch -M main"` para mudar o nome da branch para **main**, um padrão utilizado<br>
1. `git remote add origin "url do repositorio"` para passar a conexão do repositorio local para o repositorio do git<br>
1. `git push -u origin main` para enviar as modificações no repositorio.

***EX:Primeiro commit***
><sub> `git init `</sub><br>
><sub> `git add *`</sub><br>
><sub> `git commit -m "primeiro arquivo index"`</sub><br>
><sub> `git branch -M main`</sub><br>
><sub> `git remote add origin "https://github.com/JuhhSobrinho/GitTutorial.git"`</sub><br>
><sub> `git push -U origin main`</sub><br>

> [!NOTE]
> **Após dar o primeito init, branch -M e git remote,** não sera necessario dar novamente no mesmo respositorio local.

***Ex: segundo commit e git já iniciado:***
><sub> `git add *`</sub><br>
><sub> `git commit -m "Adicinando responsividade`</sub><br>
><sub> `git push -U origin main`</sub><br>

---
<br>
<br>

> [!IMPORTANT]
> Caso tenha feito alteração direto no GitHub, será necessario dar o **`GIT PULL`**<br>
> 1. `git pull` ao contrario do push que adiciona modificações ao GitHub, o **git pull** adiciona as modificações do GitHub ao repositório local.<br>
> 1. Assim caso tenha feito alteração no codigo, pelo GitHub ou até mesmo por outra maquina, é necessario dar git pull para atualizar seu repositório local.
<br>

---
<br>

## Criação de outra Branch
> 1. `git checkout -b novaBranch` para cria outra branch, cujo o nome nesse caso é **novaBranch**.
> 1. `git checkout main` para voltar para branch **main**.
> 1. `git merge novaBranch` estando dentro da main, com o comando **git merge** escolhemos qual branch queremos mesclar/juntar.
> 1. `git branch -d novaBranch` após mesclagem, caso queira **deletar a branch**, usa esse comando, no caso a branch "novaBranch" será deletada.

---
<br>
<br>
<br>

> [!TIP]
> 1. `git branch` informa a branch atual e quais **branch's** tem.<br>
> 1. `git branch -v` informa a branch atual, quais **branch's** tem e qual commits tem/ no caso o ultimo commit. <br>
> 1. `git log` mostra autor da alteração, data e qual commit.<br>
> 1. `git reset` caso cometa algum erro de add ou commit, o reset ira resetar o ultimo commit e add que tenha feito.
> 1. `git clone "url do repositorio"` para clonar seu repositório ou algum repositório publico.
> 1. `git clone "url do repositorio" --branch novaBranch --single-branch` para clonar uma branch especifica ou alguma branch especifica publica.


---
<br>

### comando para terminal

> [!TIP]
> 1. `cd` acessa diretorios "cd .\model\"  ou sai deles "cd .."<br>
> 1. `ls` lista tudo que tem no seu diretorio<br>
> 1. `touch` criar aquivo com extenção desejada, tipo .cpp, html, css etc<br>
> 1. `mkdir` criar diretorio<br>
> 1. `rkdir` deletar diretorios vazios<br>
