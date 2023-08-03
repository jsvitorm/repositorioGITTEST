
# INTRODUÇÃO

Testes práticos para aprender GIT junto com GITHUB e ver suas funcionalidades

# OBJETIVO
Conseguir fazer branchs, pull e push do/para o GitHub via Git 

# RESULTADOS

### 1.  Git GitHub Getting Started

- Nesse tópico devemos criar o repositório

- Após criar o repositório
![CriandoRepositório](/imgsREADME/criarRep.png)

- Crie uma pasta onde você deseja que o projeto fique salvo (caso o projeto ainda esteja vazio)

- Utilizando o terminal, navegue até essa pasta e insira o código: `git init`
 para inicializar o GIT nessa pasta

- Pegue o link disponibilizado ao criar o repositório

![Link Repositorio](/imgsREADME/linkRep.png)

- Insira o código: 
`git remote add origin <URL_DO_REPOSITORIO>` 
no CMD para linkar a pasta com o repositório criado no Github

![CodigoLinkarRepositorio](/imgsREADME/codigoLinkandoRep.png)


### 2.  Git GitHub Edit Code
Nessa parte vamos aprender a editar pelo GitHub, algo bem simples.

Basta clicar no icone destacado e você conseguirá editar pelo próprio GitHub. Após fazer as alterações, basta salvá-las e pronto.

![Editando READ ME Via GitHub](/imgsREADME/editViaGitHuB.png)


### 3. Pull from GitHub

Aqui nós vamos aprender a pegar atualizações do GitHub, caso nosso arquivo local esteja desatualizado em relação ao repositório!

- Utilizando `git fetch origin` podemos visualizar o que mudou no GitHub

- Depois podemos ver quantos commits nosso arquivo local está "atrasado" em relação ao repositório do GitHub utilizando `git status`

![Status](/imgsREADME/statusRep.png)

- Nesse caso estamos 2 commits atrás do repositório original

- Para pegarmos essas atualizações do repositório original, podemos utilizar merge ou pull 
- Merge serve para mesclar branchs e pull serve para pegar todas atualizações do repositório remoto

![Editando READ ME Via GitHub](/imgsREADME/me.png)

-  Usando merge vamos mesclar alterações locais do nosso branch com alterações do repositório remoto

`git merge origin/master`

![merge](/imgsREADME/mergeRep.png)


- Com pull vamos pegar todas atualizações mais recentes 

`git pull origin`

![Pull](/imgsREADME/pullRep.png)

- Pronto, nosso repositório local está atualizado 


### 4. Push to GitHub

- Após fazer alterações, podemos enviá-las ao repositório remoto por meio do push

- Para isso, primeiramente precisamos commitar via Git, isso é, adicionar as alterações ao estágio de desenvolvimento e depois comittar as mudanças

- Para adicionar ao estágio de desenvolvimento usamos 
`git add <arquivo>` ou `git add --all` (para adicionar todas alterações)

Após isso comitamos 

`git commit -m <"DESCRIÇÃO DO COMMIT">`

Agora já podemos fazer o push

`git push origin`

![Push](/imgsREADME/pushRep.png)


### 5. GitHub Branch

Para podermos criar novas branchs basta clicarmos no botão destacado e escrevermos o nome da branch que desejamos criar, após isso a branch será criada e podemos selecionar em qual branch existente desejamos trabalhar 

![Criação de branch](/imgsREADME/criabranchRep.png)

![Seleção de branch](/imgsREADME/selbranchRep.png)


### 6. Pull Branch from GitHub

Utilizando 

`git branch -a` Podemos ver todos os branchs remotos e locais existentes. 


# CONCLUSÃO
