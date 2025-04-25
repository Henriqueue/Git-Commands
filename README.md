# Git-Commands
<h2>Anotações de funcionamento do Git<h/2>

<h3>git init</h3>
Inicializa um novo repositório Git na pasta atual.

<h3>git clone [URL]</h3>
Clona um repositório remoto na sua máquina local.

<h3>git status</h3>
Mostra o estado atual do seu repositório (arquivos modificados, prontos pra commit, etc).

<h3>git add [arquivo]</h3>
Adiciona um ou mais arquivos para serem incluídos no próximo commit.

<h3>git add .</h3>
Adiciona **todos** os arquivos modificados para o próximo commit.

<h3>git commit -m "mensagem"</h3>
Cria um commit com os arquivos adicionados e a mensagem informada.

<h3>git log</h3>
Mostra o histórico de commits do repositório.

<h3>git branch</h3>
Lista todos os branches (ramificações) do projeto.

<h3>git branch -M main</h3>
Renomeia o branch atual para "main".

<h3>git checkout [nome-do-branch]</h3>
Troca para outro branch.

<h3>git checkout -b [nome-do-branch]</h3>
Cria um novo branch e já muda pra ele.

<h3>git remote add origin [URL]</h3>
Conecta seu repositório local a um repositório remoto.

<h3>git remote -v</h3>
Mostra as URLs dos repositórios remotos vinculados.

<h3>git push -u origin main</h3>
Envia seus commits locais para o repositório remoto, criando o branch se necessário.

<h3>git pull origin main</h3>
Baixa alterações do repositório remoto e mescla com seu código local.

<h3>git merge [nome-do-branch]</h3>
Mescla o branch informado com o branch atual.

<h3>git diff</h3>
Mostra as diferenças entre os arquivos modificados e o último commit.

<h3>git reset [arquivo]</h3>
Remove o arquivo da área de staging, mas **não** apaga alterações.

<h3>git reset --hard</h3>
Volta todo o repositório para o último commit (⚠️ perde tudo que não foi commitado!).

<h3>git stash</h3>
Salva temporariamente suas alterações para poder trocar de branch sem perder nada.

<h3>git stash pop</h3>
Restaura as alterações guardadas pelo `git stash`.

<h3>git config --global user.name "Seu Nome"</h3>
Define seu nome de usuário global do Git.

<h3>git config --global user.email "seu@email.com"</h3>
Define seu e-mail global do Git.

<h3>git config --list</h3>
Lista todas as configurações ativas do Git.

<h3>git rm [arquivo]</h3>
Remove um arquivo do repositório e do sistema de arquivos.

