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
- Com o nosso repositório local criado, precisamos criar um repositório remoto no Github. 

### Criando repositório remoto no Github

- Com uma conta já criada no Github, vamos criar um novo repositório. 
- No Github,  vai em seus repositórios, depois em novo, lá vamos dar nome e um descritivo opcional ao nosso repositório. Nas opções de público e privado, pode se optar por manter os seus códigos ou trabalhos, livre (público), para acesso de outras pessoas ou restrito (privado).
- O Github já te dá a opção de criar um README, que tem como função criar uma capa do nosso repositório, informações iniciais, como um índice de conteúdo.
- Preenchido todas as opções, é só ir lá no final da pagina e clicar no botão criar repositório. 
- O Github vai gerar uma URL, e ele vai passar algumas instruções do que deve ser feito, para apontar o nosso repositório local ao repositório remoto. 
- Vamos copiar a URL gerada pelo Github, e lá no Git vamos empurra o nosso repositório local ao repositório remoto. 

## Voltando ao Git

- Vamos digitar o comando, **git** **remote** **add** **origin** **+** URL gerada pelo Github. Logo em seguida vamos verificar as listas de repositórios remotos que temos cadastradas com o comando **git** **remote** **-v**. Ele vai retornar todas as listas cadastradas.
- Para identificar se não há pendências nenhuma no repositório vamos executar o comando **git** **status**, ele vai nos retornar se há algum trabalho que precisa ser adicionado **git** **add** ou que necessita realizar o **commit**. 
- Tudo ok, vamos empurrar o nosso repositório local para o remoto, com o comando **git** **push** **origin** **main**, quando falamos empurrar o código, é porque a tradução do comando executado é exatamente essa.
- Agora nós temos o nosso repositório local, lá no nosso repositório remoto. 

