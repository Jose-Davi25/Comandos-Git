##### Arquivo de Teste de Git e GitHub ####

Olá, Mundo!

#### Comandos para o Terminal do Git ####

- `vim nome.md` → Criar um arquivo.

Adicionar Todos os Arquivos
- `git add nome.md` → Adicionar as modificações ao arquivo.
- `git add . ou git add --all` → Adiciona todas as modificações (arquivos novos, modificados e deletados) ao stage.

Commit em Todos os Arquivos
- `git commit -am "comentário"` → Salvar/enviar as modificações do arquivo para o repositório local.

Criar e Mudar para uma Nova Branch
- `git branch nome-da-branch` → Cria uma nova branch.
- `git checkout nome-da-branch` → Muda para a branch criada.
- `git checkout -b nome-da-branch` → Cria e muda para a nova branch em um único comando.
- `git checkout main` → Muda para a branch main.

Conectar o repositório local ao remoto:
- `git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git` → Conecta o repositório local ao remoto.
- `git remote -v` → Verifica se o repositório remoto foi adicionado corretamente.

Enviar o código para o repositório remoto
- `git push origin master` → Enviar as alterações para o repositório online.
- `git push --all origin` → Envia todas as branches locais para o repositório remoto.
- `git push origin --tags` → Envia todas as tags para o repositório remoto.

Sincronizar o Repositório Local com o Remoto
- `git fetch origin` → Busca as alterações do repositório remoto sem aplicar no repositório local.
- `git pull origin main` → Puxa as alterações da branch main do repositório remoto e aplica no repositório local.

Tags
- `git tag nome-da-tag` → Cria uma tag no commit atual.
- `git tag → Lista todas` as tags.
- `git push origin nome-da-tag` → Envia uma tag para o repositório remoto.
- `git push origin --tags` → Envia todas as tags para o repositório remoto.

Desfazer Alterações
- `git checkout -- nome-do-arquivo` → Desfaz as alterações no arquivo, revertendo para o último commit.
- `git reset HEAD nome-do-arquivo` → Remove o arquivo do stage, mas mantém as alterações no diretório de trabalho.
- `git revert commit-hash` → Cria um novo commit que desfaz as alterações de um commit específico.

- `git log` → Exibir o histórico de commits.

- `git shortlog` → Exibir um resumo dos commits organizados por autor.

- `git status` → Verificar o status do repositório.

- `git diff` → Mostrar diferenças entre versões de arquivos.

- `git reset --soft` → Resetar o último commit mantendo as alterações no stage.

- `git reset --mixed` → Resetar o último commit mantendo as alterações no diretório de trabalho.

- `git reset --hard` → Resetar completamente o último commit, descartando todas as alterações.

#### Comandos de Navegação ####

- `cd nome-da-pasta/` → Entrar em uma pasta.

- `cd ..` → Voltar para a pasta anterior.

- `rm nome-da-pasta` ou `rm nome-do-arquivo` → Remover uma pasta ou arquivo.

- `mv nome-da-pasta` ou `mv nome-do-arquivo` → Mover ou renomear uma pasta ou arquivo.
