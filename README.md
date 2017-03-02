# Tutorial Do GitHub Em Português

        Tutorial Do GitHub Em Português


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
 
 Boas edições! Agora que você tem mudanças em um branch do master,
você poderá abrir um pull request(solicitação de mudança).

 Pull Requests são o coração da colaboração no GitHub. Quando você
abre um pull request está propondo suas mudanças e requisitando que
alguém reveja e use sua contribuição e junte elas aos seus branchs.
Pull requests mostra diffs, ou diferenças, do conteúdo vindo de
ambos os branches. As mudanças, adições, e subtrações são mostradas
em verde e vermelho.

 Assim que você fizer uma commit, você pode abrir uma pull request
e começar uma discução, mesmo depois que o código estiver 
terminado.

 Usando o @mention system do GitHub em sua mensagem de pull 
request, você pode perguntar por feedback(resposta sobre qualidade) de uma pessoa específica ou times, se eles estiverem
no hall ou afastados em 10 no fuso horário.

 Você pode inclusive abrir pull requests em seu próprio repositório
e mesclá-las por si. Esse é um ótimo caminho para aprender o fluxo
do GitHub antes de trabalhar em projetos maiores.

  Abrir uma Pull Request para mudanças para o README

 Passos:
 1. Click na aba Pull Requests, então na página Pull Request, click
no botão verde New pull request.
 2. Selecione o branch que você fez, readme-edits(ou outro nome que
você tenha dado. Ex: edições-minhas), para comparar com o master(o
original).
 3. Olhe suas mudanças em diffs na página Compare, tenha certeza
de que elas são o que você deseja submeter(ou enviar).
 4. Quando você estiver satisfeito que são essas mudanças que você
deseja enviar, click no grande botão verde Create Pull Requests.
 5. Dê a sua pull request um título e escreva uma breve descrição
das suas mudanças.

 Quando você tiver terminado sua mensagem, click Create pull
 request!

 Dica: Você pode usar emoji e drag and drop images and gifs nos 
comentários e Pull Requests.

 
          Passo 5. Fundir seu Pull Request

 No passo final, é hora de trazer e juntar suas mudanças - mesclar
seus ramos readme-edits no ramo master(master branch).
 1. Click no botão verde Merge pull request para mesclar as 
mudanças ao master.
 2. Click Confirm merge.
 3. Vá em frente e delete o branch, desde que as suas mudanças
tenham sido incorporadas, com o botão Delete branch na caixa roxa.
 

 Celebre!

 Ao completar este tutorial, você aprendeu a criar um projeto e 
realizar pull requests no GitHub!

 Aqui está o que você completou nesse tutorial:
 Criar um repositório de fonte aberta(open source);
 Começar e gerenciar um novo branch;
 Mudar um arquivo e comitar suas mudanças para o GitHub;
 Abrir e mesclar uma Pull Request;

 Dê uma olhadano seu perfil GitHub e você verá seu novo quadro
de contribuições!


 Para aprender mais sobre o poder das Pull Requests, nós 
recomendamos ler o GitHub Flow Guide. Você igualmente talvez visite
 GitHub Explore e se envolva em um projeto Open Source.

 Dica: Dê uma olhada em nossos outros Guias, canal do YouTube e
On-Demand Training(treinamento sob demanda) para mais em how to 
get started with GitHub(como começar com GitHub).


tutorial original em inglês https://guides.github.com/activities/hello-world/
tradução: DanielProjetos
 
