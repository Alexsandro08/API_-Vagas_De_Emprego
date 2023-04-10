[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=ffffff&size=35&center=true&vCenter=true&width=1000&lines=Api+Vagas+de+Emprego;)](https://git.io/typing-svg)

<img src="./img/img.png"><br>

<a href="https://shy-moon-6673.fly.dev/" target="_blank">Link do Projeto 🔗</a><br>

<h2>Resumo do Projeto 🧾<h2>
<p>Este projeto descreve uma simulação de API de vagas. A API permite que os usuários se registrem como empregadores, criem um perfil, publiquem  para os canditatos verem a vagas disponivéis de emprego e se candidatem a vagas em aberto.(obs:Vagas fictícias)</p><br>


<h2>Como Utilizar a aplicação 💻<h2>
<ul>
    <li>O empregador deve ir no botão "Abrir vaga"</li>
    <li>Colocar os dados da vaga que ele quer anunicar</li>
    <li>Ao finalizar ele pode apertar no botão "Cadastrar Vaga"</li>
    <li>Para ver a vaga anunciada ele pode apertar no botão "Ver Vaga"</li>
    <li>Por fim para pesquisar as vagas pode apertar na barra de pesquisa acima e digitar o nome da vaga que procura</li>

    

</ul> <br>

<img src="./img/api03.gif"> <img src="./img/api01.gif"> <img src="./img/api02.gif"> <br>

<h2>Funcionalidades ⚙️</h2>
 <ul>
 <li>Busca</li> 
 <li>Anúncio de vagas</li>
 <li>Indentificar vagas novas</li>
 <li>Vagas em Destaque</li>
</ul><br>
 


<h2>Tools ⚒️<h2>
<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"> 
<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge">
<img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"><br> 
<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"> 
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">

<br><h2>EndPoints 🗔</h2>
<h4>Parâmetros
<ul>
    <li>Título (obrigatório): título da vaga.</li>
    <li>Salário (obrigatório): salário do cargo.</li>
    <li>Nome da Empresa (obrigatório).
    <li>Email (obrigatório):Email para contato.</li>
</ul>
<p>MÉTODO USADO DA API</p>
 <a href="#">Método: Post</a><br>
 <a href="#">Método: Get</a>


<ul> <br>
    <li>Dependencias do projeto "Express"</li>
    <li>Pasta rotas define a rota da página "Cadastrar rotas"</li>
    <li>No arquivo "app" chama todas as dependecias necessária como o bodyParser,Sequelize, o banco de dados "SQLite" , express-handlebars, método "Path" (caminho), por fim o método "domain", que permite a criação de domínios de campos que podem ser aplicados a campos das tabelas, restringindo o conjunto de valores aceitos para inclusão e/ou alteração dos dados.
    <li>Na pasta "Views" contém a pasta "Layout" que tem o arquivo "main.handlebars" onde a função dele é onde está os links para as rotas da página principal e para página de cadastrar vagas</li>
    <li>O arquivo "add.handlebars" é onde contém o contéudo de cadastramento de vagas, nele está o formulário</li>
    <li>No arquivo "view.handlebars" está as informações da vagas que é buscada no banco de dados ao adicionar os requerimentos pedido</li>
    <li>Por fim o "index.handlebars" é onde está a página principal</li>
</ul>

<h2>Links para rodar esse projeto 🔗</h2>

````bash
# Clonar projeto
$ gh repo clone Alexsandro08/API_Vagas_De_Emprego

#Entrar no diretorio
$ cd API_Vagas_De_Emprego

#Instalar dependências
$ npm install

````

<h2>CONCLUSÃO FINAL 📝</h2>
<p>O projeto foi criado para demonstrar a habilidade de criação para projetos reais, com diversas funcionalidades adicionada para a aplicação ficar satisfátoria para o usuário integarir.</p>
