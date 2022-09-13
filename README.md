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

# STYLE-HOME.CSS #

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
			<form>
				<label for="nomeesobrenome">Nome e sobrenome</label>
               			<input type="text" id="nomeesobrenome">

               			<label for="email">Email</label>
              			<input type="text" id="email">

               			<label for="telefone">Telefone</label>
               			<input type="text" id="telefone">

			       <label for="mensagem">Mensagem</label>
			       <textarea cols="70" rows="10" id=mensagem></textarea>

	            		<div>
					<p>Como prefere o nosso contao?</p>
				        <label for="radio-email">Email</label>
				        <input type="radio" name="contato" value="email" id="radio-email">

				        <label for="radio-telefone">Telefone</label>
				        <input type="radio" name="contato" value="telefone" id="radio-telefone">

				        <label for="radio-whatsapp">Whatsapp</label>
				        <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp">
				</div>
				
            			<label><input type="checkbox">Gostaria de receber nossas novidades por email?</label>

            			<input type="submit" value="Enviar formulário">	       
			</form>
		</main>


		<footer>
			<img src="logo-branco.png">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>

# STYLE.CSS 3 #

main {
	width: 0 auto;
	margin: 940px;
}

form {
	margin: 40px 0;
}

form label {
	display: block;
	font-size: 20px;
	margin: 0 0 10px;
}

form input {
	display: block;
	margin: 0 0 20px;
	padding: 10px 25px;
	width: 50%;
}
