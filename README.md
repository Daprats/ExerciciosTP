Funções do git

git init
- iniciar novo projeto com git

git add <nome-arquivo>/.
- add os arquivos que estão porntos para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no historicos

git log
- mostra os ultimos commits, log de alteraçoes

git status 
- como estaa o estado das nossas ramificaçoes

git diff 
- mostra o que foi alterado
- o que tem de alteracao na ramificacao

git merge 
- merge ramificaçoes, mescla ramificacoes

git branch
- mostra a branch atual

git checkout
- muda pra essa branch

git branch -b <nome-da-branch>
- cria uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositorio remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositorio remoto e joga para nossa maquina

git fetch
- atualiza o novo historico local de acordo com o historico salvo no repositorio
- sincronização do local com o remoto