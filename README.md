# meu-priem-site
Aprendendo html e css

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="Um amor em cada detalhe">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venha me conhecer</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="programador.png" alt="programador">
        <nav class="menu">
            <a href="soueu.html" class="menu-item">Quem sou</a>
            <a class="menu-item">Projetos</a>
            <a class="menu-item">Dúvidas</a>
        </nav>
    </header>

    <main class="conteudo">
        <section class="conteudo-principal">
            <div class="conteudo-principal-escrito">
                <h1 class="conteudo-principal-titulo">Thielle Ferreira</h1>
                <h2 class="conteudo-principal-subtitulo">Desenvolvedor Júnior. Com conhecimento em várias tecnologias.
                    <br> E buscando meu lugar ao sol. <br><br><br>
                </h2>
                <button class="conteudo-principal-esrito-botao"><strong>Contatos</strong></button>
            </div>
            <img class="conteudo-principal-imagem" src="Group 4 (1).png" alt="anel">

        </section>

        <section class="conteudo-secundario">

            <h3 class="conteudo-secundario-titulo">Venha me conhecer e fazer seu pedidos</h3>
            <p class="conteudo-secundario-paragrafo"><strong>HTML</strong> -
                Linguagem Básico ,<strong>CSS</strong> Estilo da pagina, <strong> JS</strong> - Interatividade</p>
            <p class="conteudo-secundario-paragrafo"><strong>Conhecimento em Analista de Dados / Phyton / SQL</strong>
            </p>
            <p class="conteudo-secundario-paragrafo"><strong>E conhecimento em Metodologia Agiles</strong></p>
        </section>
    </main>

    <footer class="rodape">
        <h1>Dev. Júnior - Thielle Ferreira</h1>
    </footer>

</body </html>

/*meu css*/

@import url('https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

/* codigo para toda a pagina*/
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    text-decoration: none;
}

body {
    font-size: 100%;
    background: linear-gradient(68.15deg, #2F2325 16.62%, #8E5D52 85.61%);
}

h2 {
    font-family: 'Sarala';
    font-style: italic;
}

/*inicio da pagina*/
.cabecalho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
}

.cabecalho-imgem {
    height: 72px;
}

.menu {
    display: flex;
    gap: 32px;
    color: whitesmoke;
    font-family: 'Lobster', cursive;
    font-weight: 500;
    font-size: 30px;
}

.menu-item {

    color: white;
    display: flex;
    border: none;
}

.menu-item :hover {
    box-shadow: 0 0 10px 0 #2F2325 inset, 0 0 10px 4px #8E5D52;
}

.conteudo {
    margin-bottom: 48px;
    border-top: 0.4px solid whitesmoke;
}

.conteudo-principal {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
}

.conteudo-principal-escrito {
    display: flex;
    flex-direction: column;
    gap: 32px;
}

.conteudo-principal-titulo {
    font-family: 'Lobster', cursive;
    font-weight: 40;
    font-size: 64px;
    color: antiquewhite;
}

.conteudo-principal-subtitulo {

    font-weight: 400;
    font-size: 22px;
    color: antiquewhite;
    justify-items: auto;
}

/* CODIGO PARA O BOTAO BRILHOSO*/
.conteudo-principal-esrito-botao {
    background-color: rgba(236, 214, 196, 1);
    width: 180px;
    height: 60px;
    border: none;
    box-shadow: 4px 5px 4px rgba(13, 13, 13, 0.25);
    border-radius: 20px;
    font-family: 'Roboto', sans-serif;
    font-size: 20px;
}

.conteudo-principal-esrito-botao:hover {
    box-shadow: 0 0 10px 0 #2F2325 inset, 0 0 10px 4px #8E5D52;
}

.conteudo-secundario {
    color: #FFF2E7;
    font-family: 'Roboto', sans-serif;
    font-size: 20px;
    align-items: center;
    margin: 400;
}

.conteudo-principal-imagem {
    height: 430´x;
}

.conteudo-secundario {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;
}

.conteudo-secundario-titulo {
    border-top: 0.4px solid #FFF2E7;
    padding-top: 40px;
    font-weight: 400;
    font-size: 20px;
    color: #FFF2E7;
    margin-bottom: 16px;
    font-family: 'Lobster', cursive;
}

.conteudo-secundario-paragrafo {
    font-family: 'Sarala';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    text-align: center;
    color: #ECD6C4;
}

footer {
    color: white;
    align-items: center;
    font-size: 20px;
    font-family: 'Lobster', cursive;
    display: flex;
}

.rodape {
    border-top: 0.4px solid #FFF2E7;
    padding: 32px;
    display: block;
    margin: 0;
    text-align: center;
}

/*SEGUNDA PAGINA QUEM SOU EU*/

.cabecalho1 {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
}

.conteudo-principal-escrito1 {
    display: block;
    margin-left: 50px;
    margin-right: 50px;
    padding: 5%;
}

.cabecalho-imagem1 {
    display: block;
    margin-left: 60px;
    margin-left: 50px;
    padding: 40px;
    border-radius: 50%;
}

.eu1 {
    color: white;
    font-size: 60px;
    font-family: 'Lobster', cursive;
    animation: 2, ease-in-out infinite;
}
