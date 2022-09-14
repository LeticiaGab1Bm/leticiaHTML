# HTML 1 #

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Barbearia Alura</title>
        <link rel="stylesheet" href="style-home.css">
    </head>

    <body>
        <header>
            <h1 class="titulo-principal">Barbearia Alura</h1>
        </header>        
        <img src="banner.jpg">
        <div class="principal">
            <h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>

            <p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. 
            Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

            <p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

            <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
            O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
        </div>

        <div class="beneficios">
            <h3 class="titulo-centralizado">Benefícios</h3>

            <ul>
                <li class="itens">Atendimento aos Clientes</li>
                <li class="itens">Espaço Diferenciado</li>
                <li class="itens">Localização</li>
                <li class="itens">Profissionais Qualificados</li>
            </ul>

            <img src="beneficios.jpg" class="imagembeneficios">
        </div>
    </body>
</html>

# STYLE.CSS #

body {
    
}


#banner {
    width: 100%
}


.principal {
    background: #CCCCCC;
    padding: 30px;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
    text-align: center;
}

p {
    text-align: center;
}

#missao{
    font-size: 20px
}

em strong {
    color: #FF0000;
}

.itens {
    font-style:italic;
}

.beneficios{
    background: #FFFFFF;
    padding: 20px;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}

.imagembeneficios{
    width: 50%;
}

# HTML 2 #

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Produtos - Barbearia Alura</title>

        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <div class="caixa">
                <h1><img src="logo.png"></h1>

                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <main>
            <ul class="produtos">
                <li>
                    <h2>Cabelo</h2>
                    <img src="cabelo.jpg">
                    <p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir.</p>
                    <p class="produto-preco">R$ 25,00</p>
                </li>
                <li>
                    <h2>Barba</h2>
                    <img src="barba.jpg">
                    <p class="produto-descricao">Corte e desenho profissional de barba.</p>
                    <p class="produto-preco">R$ 18,00</p>
                </li>
                <li>
                    <h2>Cabelo + Barba</h2>
                    <img src="cabelo+barba.jpg">
                    <p class="produto-descricao">Pacote completo de cabelo e barba.</p>
                    <p class="produto-preco">R$ 35,00</p>
                </li>
            </ul>
        </main>

        <footer>
            <img src="logo-branco.png">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019 </p>

        </footer>

    </body>
</html>

# STYLE.CSS 2 #

header {
    background: #BBBBBB;
    padding: 20px 0;
}

.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}

nav a:hover {
    color: #C78C19;
    text-decoration: underline;
}

.produtos {
    width: 940px;
    margin: 0 auto;
    padding: 50px 0;
}

.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
    border: 2px solid #000000;
    border-radius: 10px;
}

.produtos li:hover {
    border-color: #C78C19;
}

.produtos li:active {
    border-color: #088C19;
}

.produtos li:hover h2 {
    font-size: 34px;
}

.produtos h2 {
    font-size: 30px;
    font-weight: bold;
}

.produto-descricao {
    font-size: 18px;
    font-size: 22px;
    font-weight: bold;
    margin-top: 10px;
}

footer {
    text-align: center;
    background: url("bg.jpg");
    padding: 40px 0;
}

.produto-preco {
}

.copyright {
    color: #000000;
    font-size: 13px;
    margin: 20px;
}

# HTML 3 #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Contato - Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo.png" alt="Logo da Barbearia Alura"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contato.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<main>
			<form>
               <label for="nomeesobrenome">Nome e sobrenome</label>
               <input type="text" id="nomeesobrenome" class="input-padrao" required>

               <label for="email">Email</label>
               <input type="email" id="email" class="input-padrao" required placeholder="seuemail@dominio.com">

               <label for="telefone">Telefone</label>
               <input type="tel" id="telefone" class="input-padrao" required placeholder="(xx) xxxxx-xxxx">

               <label for="mensagem">Mensagem</label>
               <textarea cols="70" rows="10" id=mensagem class="input-padrao" required></textarea>

	            <fieldset>
	               <legend>Como prefere o nosso contao?</legend>
	               <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

	               <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

	               <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>Whatsapp</label>
	            </fieldset>

	            <fieldset>
		            <legend>Qual horário prefere ser atendido?</legend>
		            <select>
		            	<option>Manhã</option>
						<option>Tarde</option>
		            	<option>Noite</option>
	            	</select>
	        	</fieldset>

            	<label class="checkbox"><input type="checkbox" checked>Gostaria de receber nossas novidades por email?</label>

            	<input type="submit" value="Enviar formulário" class="enviar">
            </form>

            <table>
            	<thead>
	            	<tr>
	            		<th>Dia</th>
	            		<th>Horário</th>
	            	</tr>
	            </thead>

	            <tbody>
	            	<tr>
	            		<td>Segunda</td>
	            		<td>8h ~ 20h</td>
	            	</tr>
	            	<tr>
	            		<td>Quarta</td>
	            		<td>8h ~ 20h</td>
	            	</tr>
	            	<tr>
	            		<td>Sexta</td>
	            		<td>8h ~ 20h</td>
	            	</tr>
	            </tbody>
            </table>


		</main>

		<footer>
			<img src="logo-branco.png" alt="Logo da Barbearia Alura">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>

# STYLE.CSS 3 #

header {
	background: #BBBBBB;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 34px;
}

.produtos h2 {
	font-size: 30px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;
}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
	margin-top: 10px;
}

footer {
	text-align: center;
	background: url("bg.jpg");
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}

main {
	width: 940px;
	margin: 0 auto;
}

form {
	margin: 40px 0;
}

form label, form legend {
	display: block;
	font-size: 20px;
	margin: 0 0 10px;
}


.input-padrao {
	display: block;
	margin: 0 0 20px;
	padding: 10px 25px;
	width: 50%;
}

.checkbox {
	margin: 20px 0;
}

.enviar {
	width: 40%;
	padding: 15px 0;
	background: orange;
	color: white;
	font-weight: bold;
	font-size: 18px;
	border: none;
	border-radius: 5px;
	transition: 1s all;
	cursor: pointer;
}

.enviar:hover {
	background: darkorange;
	transform: scale(1.2);
}

table {
	margin: 20px 0 40px;
}

thead {
	background: #555555;
	color: white;
	font-weight: bold;
}

td, th {
	border: 1px solid #000000;
	padding: 8px 15px;
}

# HTML 4 #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Produtos - Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo.png"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contato.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>
		
		<main>
			<ul class="produtos">
				<li>
					<h2>Cabelo</h2>
					<img src="cabelo.jpg">
					<p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
					<p class="produto-preco">R$ 25,00</p>
				</li>
				<li>
					<h2>Barba</h2>
					<img src="barba.jpg">
					<p class="produto-descricao">Corte e desenho profissional de barba</p>
					<p class="produto-preco">R$ 18,00</p>
				</li>
				<li>
					<h2>Cabelo + Barba</h2>
					<img src="cabelo+barba.jpg">
					<p class="produto-descricao">Pacote completo de cabelo e barba</p>
					<p class="produto-preco">R$ 35,00</p>
				</li>
			</ul>
		</main>

		<footer>
			<img src="logo-branco.png">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>

# STYLE.CSS 4 #

.banner {
	width: 100%;
}

.titulo-principal{
	text-align: center;
	font-size: 2em;
	margin: 0 0 1em;
	clear: left;
}

.principal {
	padding: 3em 0;
	background: #FEFEFE;
	width: 940px;
	margin: 0 auto;
}

.principal p {
	margin: 0 0 1em;
}

.principal strong {
	font-weight: bold;
}

.principal em {
	font-style: italic;
}

.utensilios {
	width: 120px;
	float: left;
	margin: 0 20px 20px 0;
}

.mapa {
	padding: 3em 0;
	background: linear-gradient(#FEFEFE,#888888);
}

.mapa p {
	margin: 0 0 2em;
	text-align: center;
}

.mapa-conteudo {
	width: 940px;
	margin: 0 auto;
}

.beneficios {
	padding: 3em 0;
	background: #888888;
}

.conteudo-beneficios {
	width: 640px;
	margin: 0 auto;
}

.lista-beneficios {
	width: 40%;
	display: inline-block;
	vertical-align: top;
}

.itens {
	line-height: 1.5;
}

.itens:first-child {
	font-weight: bold;
}

.itens:before {
	content: "🟊";
}

.imagem-beneficios {
	width: 60%;
	opacity: 1;
	transition: 400ms;
	box-shadow: 10px 10px 10px 0 #000000;
}

.imagem-beneficios:hover {
	opacity: 0.3;
}

.video {
	width: 560px;
	margin: 2em auto;
}

/*Celular página inicial*/

@media screen and (max-width: 480px) { 
    .caixa, .principal, .conteudo-beneficios, .mapa-conteudo, .video {
        width: auto;
    }

    h1 {
    text-align: center;
	}

	nav {
    position:static;
	}

	.lista-beneficios, .imagem-beneficios {
    width: 100%
	}

}
