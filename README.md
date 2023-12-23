# GitTutorial
## Inicializando Git e dando primeiro commit
1. `git init` para **inicializar** o repositorio<br>
1. `git add .` para separar os arquivos para o **commit**<br>
1. `git commit -m "primeiro commit"` para dar o real commit com sua mensagem e preparação para o **push**<br>
1. `git branch -M main"` para mudar o nome da branch para **main**, um padrão utilizado<br>
1. `git remote add origin "url do repositorio"` para passar a conexão do repositorio local para o repositorio do git<br>
1. `git push -u origin main` para enviar as modificações no repositorio.

 EX:
><sub> `git init `</sub><br>
><sub> `git add *`</sub><br>
><sub> `git commit -m "primeiro arquivo index"`</sub><br>
><sub> `git branch -M main`</sub><br>
><sub> `git remote add origin "https://github.com/JuhhSobrinho/GitTutorial.git"`</sub><br>
><sub> `git push -U origin main`</sub><br>

> [!NOTE]
> Após dar o primeito init, branch -M e git remote, não sera necessario dar novamente no mesmo respositorio local.

Ex: segundo commit e git já iniciado:
><sub> `git add *`</sub><br>
><sub> `git commit -m "Adicinando responsividade`</sub><br>
><sub> `git push -U origin main`</sub><br>

---
<br>
<br>
<br>

> [!IMPORTANT] GIT PULL
> Caso tenha feito alteração direto no GitHub, será necessario dar o **GIT PULL**

1. `git pull` ao contrario do push que adiciona modificações ao GitHub, o **git pull** adiciona as modificações do GitHub ao repositório local.

1. Assim caso tenha feito alteração no codigo, pelo GitHub ou até mesmo por outra maquina, é necessario dar git pull para atualizar seu repositório local.

