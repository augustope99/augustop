
# DIO | GIT E GITHUB

Diretorios para armazenar arquivos do curso de GIT E
GITHUB da DIO [Digital Inovation One](https://web.dio.me/).

## 📚 DOCUMENTAÇÃO
- [Documentação GIT](www.git-scm.com/doc)
- [Documentação GITHUB](https://docs.github.com)

## 🖥️ RESUMO DAS AULAS
 |      AULAS         |     RESUMO      |
 |--------------------|-----------------|
|Comandos do terminal 
 git clone | Clona um repositorio git existente para uma pasta do seu computador
 git commit | Para gravar alterações no repositorio
 git pull | é usado para baixar conteúdo remoto de um repositório Git e atualizar o seu repositório local
 git push | é usado para enviar as alterações locais para o repositório remoto. Ele é usado para compartilhar as alterações feitas no seu repositório local com outros desenvolvedores ou para armazenar as alterações em um repositório remoto.
 mkdir | serve para criar uma pasta é so digitar o comando e na frente colocar o nome da pasta que você deseja.
 cd | serve para navegar entre pastas
 git init | é usado para inicializar um novo repositório Git em um diretório existente. Ele cria um novo diretório .git no diretório atual e inicializa o repositório local.
 cat config | ver o git (tem que usar dentro da pasta git)
 git remote add origin "URL do repositorio" | Para conectar o repositorio local com o repositorio remoto.
 git clone url --branch "nome da branch"-1  --single-branch | Para clonar um repositorio com varias branchs e quer escolher so uma.
 git status | Para ver o status da area de trabalho(staged)
 touch "nome do arquivo.md" | Cria um arquivo vazio.
 echo "a palavra ou texto/pasta que quiser" />.gitignore | Cria um arquivo que tenha algo que você quer escrito dentro.
echo >.gitignore | remove a escrita de dentro do arquivo.
rm -rf.git | Remove um diretorio forçadamente e todos os seus arquivos.
git restore "o nome do arquivo que foi modoficado" | Restaura um arquivo para seu estado antes de ser modificado antes do salvamento.(ATENÇÃO ESSE COMANDO DESCARTA TODAS AS ALTERAÇÕES FEITAS NO REPOSITORIO LOCAL ANTES DE SER SALVO)
git commit --amend -m" o texto que você quer que seja apresentado" | Altera a mensagem do commit
git commit --amend | abre um terminal para você fazer alteração do texto do commit(ASSIM QUE O TERMINAL ABRIR BASTA APERTAR "i" para modificar depois para sair aperte "esc", depois ": wq")
git reset --soft | Volta os arquivos para o Staged
git reset --mixed | Tem a mesma função do Soft PORÉM ele volta os arquivos para o estado antes de ir pro Staged.
|Staged | É quando sobe o arquivo para a conexão com o repositorio do GITHUB e do computador(Repositorio local).




