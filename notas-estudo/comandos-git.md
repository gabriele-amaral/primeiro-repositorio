## Comandos utilizados no Git:

> HISTÓRICO

- _**git log**_ - _Mostrar todos os commits, começando pelo mais novo_

- _**git log -p < file >**_ - _Mostrar mudanças ao longo do tempo para um arquivo específico_

- _**git blame < file >**_ - _Mostra quem alterou o quê e quando em < file >_

  

> MUDANÇAS LOCAIS

- _**git status**_ - _Arquivos alterados em seu diretório de trabalho_
- _**git digg**_ - _Mudanças em arquivos rastreados_
- _**git add .**_ - _Adicione todas as mudanças atuais para o próximo commit_
- _**git add . -p < file >**_ - _Adicione algumas mudanças em < file > para o próximo commit_
- _**git commit -a**_ - _Confirmar todas as alterações locais em arquivos rastreados_
- _**git commit**_ - _Confirmar alterações previamente preparadas_
- _**git commit --amend**_ - _Mude o último commit_



> ATUALIZAR E PUBLICAR

- _**git remote -v**_ - _Lista todos os controles remotos configurados atualmente_
- _**git remote show < remote >**_ - _Mostrar informações sobre um controle remote_
- _**git remote add < shortname > < url >**_ - _Adicione um novo repositório remoto, denomin+ado < remote >_
- _**git fetch < remote >**_ - _Baixe todas as alterações de < remote >, mas não integre no HEAD_

- _**git pull < remote > < branch >**_ - _Baixe as alterações e marque/integre diretamente no HEAD_
- _**git push < remote > < branch >**_ - _Publique as alterações locais remotamente_
- _**git branch -gh < remote/branch >**_  - _Exclua uma filial no controle remoto_
- _**git push --tags**_ - _Publique suas tags_
- _**git push**_ - _Publicar_



> DESFAZER

- _**git reset -hard HEAD**_ - _Descarte todas as mudanças locais em seu diretório de trabalho_
- _**git checkout HEAD < file >**_ - _Descarte as alterações locais em um arquivo específico_
- _**git revert < commit >**_ - _Reverter um commit (produzindo um novo commit com mudanças contrárias)_
- _**git reset -hard < commit >**_ - _Redefina o ponteiro HEAD para um commit anterior... e descarte todas as alterações desde então_
- _**git reset < commit >**_ - _... e preserva todas as mudanças como mudanças não planejadas_
- _**git reset -keep < commit >**_ - _... e preserva as mudanças locais não comprometidas_



> BRANCHES

- _**git branch -av**_ - _Listar todos os ramos existentes_
- _**git checkout < branch >**_ - _Mudar ramo HEAD_
- _**git checkout < new-branch >**_ - _Crie uma nova filial com base_
- _**git checkout--track < remote branch >**_ - _Crie uma nova filial com base_
- _**git branch -d < branch >**_ - _Deletar uma filial local_
- _**git tag < tag-name >**_ - _Marque o commit atual com uma tag_



> FUNDIR E REBASE

- _**git merge < branch >**_ - _Funda < branch > em seu HEAD atual_
- _**git rebase < branch >**_ - _Rebase seu HEAD atual em < branch >_
- _**git rebase --abort**_ - _Abortar um rebase_
- _**git rebase --continue**_ - _Continue um rebase após resolver os conflitos_
- _**git mergetool**_ - _Use a ferramenta de fusã configurada do tour para resolver conflitos_
- _**git add < resolved-file > | git rm < resolved-file >**_ - _Use o editor de tour para resolver conflitos manualmente e (após resolver) marcar o arquivo como resolvido_