# Tutorial Do GitHub Em Português
Tutorial Do GitHub

O GitHub aparentemente não é difícil de utilizar,
vamos verificar a seguir se a recíproca é verdadeira.

A seguir o tutorial oficial com as principais funcionalidades do GitHub.


   O que é GitHub?

 GitHub é uma plataforma de hospedagem de códigos para controle
de versão e colaboração. Isso permite que você e outros trablalhem
juntos em projetos de qualquer lugar.

 Este tutorial lhe ensinará o essencial do GitHub como:
repositórios(repositories), branches, commits, e Pull Requests.
Você criará seu próprio repositório Hello World(Olá Mundo) e
aprenderá a puxar o fluxo de trabalho das requisições do
GitHub's.


   Não é necessário codificar

 Para completar este tutorial, você precisará de uma conta no
GitHub.com e acesso à internet.
 Você não precisará saber como fazer códigos, usar a linha de 
comando, ou instalar Git(O software de versão de controle instalado
do GitHub).

 Dica: Abra este guia em um navegador separado (ou aba), então você
poderá ver isso enquanto completa os passos do tutorial.


   Passo 1. Crie um Repositório
   
 O repositório é usualmente usado para organizar um projeto simples.
Repositorios podem conter pastas e arquivos, imagens, vídeos, 
planilhas, e ajustes de dados - qualquer coisa que seu projeto
necessite. Nós recomendamos incluir um README(LEIA-ME), ou um 
arquivo com informações sobre o projeto. GitHub faz isto ser fácil
para adicioná-lo ao mesmo tempo em que cria o repositório. 
Além disso oferece outras opções comuns tal como um arquivo de
licensa.

 Seu repositório hello-world pode ser um local ond você guarda
ideias, recursos, ou até mesmo compartilha e discute coisas com
os outros.

   Para criar um novo repositório.

 1. No canto superior direito, próximo do seu avatar ou 
identificação, click + e então selecione New repository.
 2. Nomeie seu repositório hello-world.
 3. Escreva uma breve descrição.
 4. Selecione Initialize this repository with a README.

Dica: Ao final das opções é possível selecionar um tipos de licença
para o projeto.
Observação: Para criar repositórios privados é necessário pagar
uma taxa de U$7 (sete dólares) por mês.

 
 Passo 2. Crie um Branch

 Branching é um caminho para trabalhar em diferentes versões de um
repositório por vez.

 Por padrão seu repositório possui um branch(ramo) nomeado de 
master(mestre) que é considerado o branch definitivo
(ramo definitivo). Nós usamos os ramos para experimentar e fazer
edições antes de comitá-las para master(mestre).

  Quando você cria um ramo do master branch, você está fazendo uma
cópia ou snapshot, do mestre como se realmente fosse naquele momento
 do tempo. Se mais alguém fizer alterações ao master branch enquanto
 você trabalha em seu branch, você poderá colocá-los em suas
atualizações.

  O diagrama mostra:

 O master branch(ramo mestre);
 Um novo branch chamado FEATURE(realçar)(porque nós estamos 
fazendo um "trabalho de realçar" neste ramo);
 A jornada que FEATURE tem antes de ser mesclada com o MASTER. 
Você sempre tem salvo diferentes versões de um arquivo?
 É algo como:
  
 histórico.txt
 histórico-edições-joe.txt
 histórico-edições-revisadas-joe.txt

 Branches(Ramos) completam gols similares nos repositórios do 
GitHub.

 Aqui no GitHub, nossos desevolvedores, escritores, e designers usam
os ramos para manter o reparo de bugs e trabalhos de lançamentos
separados do nosso master branch(ramo mestre ou ramo de produção).
 Quando uma mudança está pronta, eles mesclam seus ramos ao master.

 Para criar um new branch(novo ramo)

 1. Vá ao seu repositório hello-world.
 2. Click no menu de seta(drop down) no topo da lista de arquivos
que diz branch:master (ramo:mestre).
 3. Escreva o nome do branch, readme-edits, dentro da nova
caixa de textos branch.
 4. Selecione a caixa Create branch que está em azul ou aperte
"Enter" em seu teclado.

  Agora você terá dois branches, master e readme-edições. Eles
parecem exatamente a mesma coisa, porém não por muito tempo! A 
seguir nós iremos adicionar nossas alterações ao novo branch.


   Passo 3. Fazer e comitar mudanças

 Bravo! Agora, você dentro da visualização do seu branch
readme-edições, o qual é uma cópia do master. Vamos fazer algumas
edições.

 No GitHub, as mudanças salvas são chamadas commits. Cada 
comitação possui uma mensagem Commit Message associada, que é a 
descrição explicativa do porque uma mudança em particular foi 
feita. Commit messages capturam o histórico de suas mudanças, então
outros colaboradores podem entender o que você tem feito e o 
porque.

  Fazer e comitar mudanças

 1. Click em README.md file.
 2. Click no ícone do lápis no canto superior do arquivo vizualizado para edição.
 3. No editor, escreva um pouco sobre você mesmo.
 4. Escreva uma mensagem de commit que descreve suas mudanças.
 5. Click no botão Commit changes.

 Estas mudanças serão feitas apenas para o arquivo README em seu
ramo readme-edits(apenas neste branch), então agora o conteúdo
deste branch está diferente do master(ramo principal).

 Passo 4. Abrir uma Pull Request  
