==================================================== ===========================
Comandos básicos do git
==================================================== ===========================

git init => Adiciona o projeto ao git.

git status => Exibe o status do repo que estamos trabalhando.

git add => adiciona arquivo para ser comitado

adicionar git. => adiciona vários arquivos na área de palco.

git commit => Faz commit do arquivo

git commit -a -m => Para comitar todos os arquivos no stage.

git push => Empurra os arquivos para o servidor git

git pull => Busca atualização no repo

git clone + caminho do repo => Clona repo para sua máquina

git rm => remove arquivo do repo

git mv => pode renomear ou mover um arquivo no git

git checkout => volta o arquivo para o estado original.

.gitignore => Este arquivo serve para ignorar o que não será monitorado no git.

git reset --hard + origin/main => Reseta as configurações para as mesmas definiçoes do server.

==================================================== ===========================

Trabalhando com Filial
==================================================== ===========================

git branch => Comando para verificar quantos branch temos e onde estamos trabalhando.

git branch + nome_branch => cria um novo branch

git branch -d ou --delete => deletar um branch criado

git checkout + <nome_branch> => comando para mudar de Branch

git checkout -b + <nome_branch> => cria um novo branch e muda para ele.

git merge <nome_branch> => faz união dos ramos

git stash => Comando utilizado para fazer rollback para o estado inicial do projeto, porém é possível recuperar caso seja necessário o que foi feito.

git stash list => lista todas as stash feitas até o momento

git stash apply < Numero da Stash> => recupera o stash enviado para a lixeira.

git stash show -p < Numero da Stash> => Mostra quais alterações foram feitas.

git stash clear => Limpa todas as stash

git stash drop <Número da Stash> => Exclui a stash selecionada apenas.

git tag -a -m => Cria um marco durante o desenvolvimento.

git show < nome da tag> => Mostra toda atualização feita quando foi salvar a tag

git checkout < nome da tag > => Usado para trocar de tag

==================================================== ===========================

Compartilhamento e atualização de Repo
==================================================== ===========================

git

==================================================== ===========================

Analise e teste de Repo
==================================================== ===========================

git show => Examinar objetos em um repositório Git e histórico de commits.

git diff => Mostra a diferença entre arquivos do git.

git shortlog => Mostra um histórico de commits do que foi feito no projeto.

==================================================== ===========================

Admistração de repositório
==================================================== ===========================

git clean => limpa todos os arquivos que estão untracked

git gc => Limpa arquivos que não são necessários para nosso projeto através do coletor de lixo.

git fsck => Verifica a integridade dos arquivos e sua conectividade do repo.

git reflog => Mapea todos seus passos no repo.

git archive --format zip --output main_files.zip main => comando para transformar o repo em um arquivo .zip

==================================================== ===========================