# Techblog
Projeto feito com Html e Css
<br>https://edimar-jr.github.io/Techblog/ <br>

![imagem2](https://user-images.githubusercontent.com/107490860/183243114-5c6eba3b-4b78-463b-95c6-3bbf5c60deb9.jpg)

## codigo Html

<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" type="text/css" href="estilo.css">
		<title>Techblog</title>
	</head>
	<body>
              <!--- cabeçalho--->
		<div id="area-cabecalho">

			<div id="area-logo">
				<h1>Tech<span class="blog">blog</span></h1>
			</div>

			<div id="area-menu">
				<a href="index.html">Home</a>
				<a href="index2.html">Jogos</a>
				<a href="index3.html">Celulares</a>
				<a href="index4.html">Informatica</a>
				<a href="index5.html">Eletronicos</a>
			</div>

		</div>  <!--- fim cabeçalho--->

		<!--- area de conteudo --->

		<div id="area-principal">

			<!--- abertura postagens --->

			<div id="area-postagens">

				<div class="postagens">
					<h2>Titulo da postagens</h2>
					<span class="data-postagem">Postado em 04 agosto 2022</span>

						<img width="620px" src="imagens/imagem1.jpg">

						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

						<a href="#">Leia mais</a>
				</div> <!--- fechamento postagens --->

				<!--- abertuea postagens 2 --->
				<div class="postagens">
					<h2>Titulo da postagens</h2>
					<span class="data-postagem">Postado em 01 agosto 2022</span>

						<img width="620px" src="imagens/imagem2.jpg">

						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

						<a href="#">Leia mais</a>
				</div> <!--- fechamento postagens 2 --->


			</div>

			 <!--- conteudo lateral  --->

				<div id="area-lateral">

					<div class="conteudo-lateral">
						<h3>Postagens recentes</h3>
						
						<div class="postagem-lateral">
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
							dolore magna aliqua.</p>

							<a href="#">Leia mais</a>

						</div>

	
						<div class="postagem-lateral" style="border-bottom: none;">
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
							dolore magna aliqua.</p>

							<a href="#">Leia mais</a>

						</div>	


					</div> <!--- fechamento conteudo lateral 2 --->

					<div class="conteudo-lateral">
						<h3>Categoria</h3>
						
						<a href="index.html">Top 10</a><br>
						<a href="index2.html">Jogos</a><br>
						<a href="index3.html">Celulares</a><br>
						<a href="index4.html">Informatica</a><br>
						<a href="index5.html">Eletronicos</a><br>

						
					</div> <!--- fechamento conteudo lateral 2 --->

							
				</div>

					<div id="rodape">
						Todos os direitos reservado 
					</div>

		
	</body>
</html>
	
## codigo Css
	
/*LIMPANDO AS FORMATAÇOES PADROES*/

* {
	margin: 0px;
	padding: 0px;
}

body {

	font-size: 1em;
	font-family: "trebuchet MS", helvetica, sans-serif;
	background: #e6e6e6;

}

/*layout cabeçalho*/

#area-cabecalho {

	background: #f7b600;
	padding: 15px;
	text-align: center;
		
}

#area-logo, #area-menu {

	padding: 10px;

}

#area-principal {
		
	width: 920px;
	margin: 0px auto;
	padding: 15px;

}


#area-postagens{

	width: 660px ;
	float: left;

}

#area-lateral{

	width: 240px;
	float: right;

}

.postagens {

	padding: 20px;
	margin-bottom: 20px;
	background: white;

}

.conteudo-lateral{

	background: white;
	padding: 10px;
	margin-bottom: 20px;
}

.postagem-lateral {

	font-size: 0.8em;
	padding: 5px;
	border-bottom: 1px dotted #CCC;
	
}


#rodape {

	background: #CCC ;
	clear: both;
	text-align: center;
	padding: 15px;
	;

}


/*formataçao menu*/

a {

	text-decoration: none;
}

a:link,  a:visited {

	color: #F7b600;
	
	
	

}

a:hover{

	text-decoration: underline;
	




}


#area-cabecalho a:link, #area-cabecalho a:visited {

	color: #FFF;
	padding: 8px 12px;
	

}

#area-cabecalho a:hover{
	color: #f7b600;
	background: #fff;
	text-decoration: none;


}

h1 {

	color: #4e4e4e;
	font-size: 2.5em;

}

h2 {
	color: #f7b600;

}

h3 {
	color: #565656;
	background: #f7b600;
	padding: 5px;

}

.blog {

	color: white;
}

.data-postagem {

	font-size: 0.8em;
	border-bottom: 1px solid #f4f4f4;
	padding-bottom: 10px;
	margin-bottom: 10px;
	display: block;

}

	
	

