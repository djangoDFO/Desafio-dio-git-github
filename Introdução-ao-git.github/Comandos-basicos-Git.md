# Primeiros passos no Git/Github:computer:

### Comandos básicos para sistema windows

- **dir:** Vai lista todos os diretórios contidos dentro da pasta que estamos situados.
- **cd** **+** **nome da pasta:**  Utilizado para navegar a pasta desejada.
- **cd ..** **:** Utilizado para voltar/retornar a pasta anterior.
- **Ctrl** **+** **L:** Limpa a tela do terminal.
- **ls:** Lista todos arquivos contidos dentro da pasta.
- **ls** **-a:** Vai mostrar os arquivos ocultos contidos dentro da pasta.
- **dir:** Vai listar todos diretórios. 
- **mkdir:** Utilizado para criar pastas, comando mais o nome da pasta que deseja criar. 
- **rmdir:** Utilizado para excluir pastas e tudo oque há dentro dela. Ex: rmdir workspace /s /q.
- **del:** Utilizado para excluir arquivos dentro das pastas. Ex: del workspace.

### Iniciando o Git e criando um commit

- Vamos abrir o Gitbash no repositório C:
- Com os comandos básicos aprendidos, vamos criar uma pasta em nosso computador , para iniciar o nosso projeto. Ex: workspace
- Dentro de workspace, vamos criar uma nova pasta, que vai dar o nome do nosso projeto. Ex: livro de receitas.
- Para iniciar o Git dentro desta pasta, vamos executar o comando **git** **init**, para que ele possa gerenciar e versionar o nosso código.
- Antes de executar o comando **git** **commit**, precisamos realizar uma configuração inicial de email e usuário, para que cada vez que for executar um "commit" é necessário ter um autor atrelado a ele.
- Configuração inicial de email e usuário: **git** **config** **--global** **user.email** **"diiego.oliveira28@gmail.com"** / enter. depois vamos configura usuário **git** **config** **--global** **user.name** **Oliveira** / enter.
- Agora vamos criar um arquivo do tipo markdown. Dentro da pasta livro de receitas, vamos criar o arquivo. Ex: **strogonoff-de-frango.md**.
- Após criar o arquivo contendo a receita do strogonoff de frango, vamos executar o comando: **git** **add** **"*"** ou **git** **add** **.** Para adicionar todas as modificações feitas dentro do projeto. 
- Agora vamos executar o comando: **git** **commit** **-m** **"commit inicial"**, as ("") são para colocar um comentário. É muito importante comentar a cada commit executado, para saber passo a passo do projeto. 
- 
