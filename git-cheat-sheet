# Tabela de comandos para o Git

Comando | Descrição
--- | ---
`git init` | Inicia um repositório local
`git add <arquivo>` | Adiciona arquivos especificados em cena para commit
`git commit` | Realiza commit com arquivos colocados em cena </br> `-a` : adiciona todos arquivos em cena automaticamente (Que já estejam sendo rastreados). </br> `-m <mensagem>` : define mensagem do commit.
`git pull` | Puxa repositório de origin e sincroniza com HEAD.
`git fetch` | Puxa repositório de origin e não sincroniza com HEAD.
`git push <origin> <branch>` | Sobe repositório para o GitHib. </br> `-u` : define local remoto. </br> `-f` : modo forçado.
`git rm <arquivo>` | Remove arquivos. </br> `--cached` : remove apenas do repositório local e mantém o arquivo no local de trabalho.
`git checkout <hash, branch, arquivo>` | Verifica diferenças entre o que foi apontado e estado atual, e aplica em HEAD. </br> `-b <nome> <base>` : cria nova branch baseada em outra e muda para ela. </br> `--orphan` : cria branch vazia. </br> `-- pasta/arquivo` : faz checkout somente do especificado, ex; pasta.
`git reset <arquivo, hash>` | Remove arquivos em cena. </br> `--hard` : leva para o commit desejado, apagando os posteiores.
`git branch` | Mostra lista de branches do projeto. </br> `-d` : deleta branch. </br> `-D` : deleta branch em modo forçado, mesmo que não tenha sido fundida.
`git switch <branch>` | Muda para branch.
`git merge <nome>` | Funde branch definida junto com a atual. </br> `--abort` : aborta merge em caso de conflitos. </br> `--allow-unrelated-histories` : força merge mesmo com branches totalmente diferentes.
`git status` | Mostra status, além de dicas de como proceder.
`git log` | Mostra log e hashes de commits. </br> `--oneline` : mostra versão simplificada. </br> `--graph` : mostra grafos. </br> `--all` : mostra todas as branches.
`git diff` | Mostra o que mudou em relação ao último commit e o arquivo atual.
`git remote` | Mostra repositórios remotos existentes. </br> `add <nome/origin>` : adiciona novo repositório remoto. </br> `rename <velho> <novo>` : renomeia repositório remoto. </br> `remove` : remove repositório remoto. </br> `set-head <nome>` : define como HEAD. </br> `-v` : modo verboso.
`git config` | Define ou mostra configurações. </br> `--local` : configuração apenas para repositório atual </br> `--global` : configuração global para todos os repositórios.

# Legendas
- `HEAD` : É a pasta no seu windows/unix onde se encontra os arquivos reais do projeto.

# Configurações
- `user.name <nome>` : Define/mostra nome de usuário.
- `user.email <email>` : Define/mostra email de usuário.
- `credential.helper <store>` : Define/mostra método de salvamento de credenciais de login. 
- `core.editor <editor/local>` : Define o editor padrão do git.
